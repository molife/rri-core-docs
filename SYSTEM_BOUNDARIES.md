# System Boundaries for AI Tools and Agents

## Purpose

This document defines hard safety boundaries for every AI tool, agent, automation assistant, repository assistant, documentation assistant, and future orchestration tool connected to this repository.

These boundaries protect Rays of Resilience International Ministries, Rays of Resilience Foundation, Rays of Resilience International Ministries Limited, donors, partners, children, ministry teams, websites, business platforms, payment systems, banking systems, and production operations.

This file is documentation-only. It does not authorize deployment, production access, live integrations, credential handling, legal filing changes, financial actions, payment actions, donor communications, or operational commitments.

## Scope

These rules apply to all AI-assisted work involving this repository, including:

- ChatGPT conversations and documentation drafts.
- Codex repository changes and pull requests.
- Claude Code local review or documentation work.
- Future AI agents, automation tools, orchestration layers, scripts, or integrations.
- Any tool that reads, edits, summarizes, reviews, or proposes changes based on this repository.

If another document appears to allow broader action, this boundary document takes priority unless Roman gives explicit written approval and the required review level is complete.

## Core Rule

AI tools and agents may support documentation, planning, review, and safe repository hygiene only. They must not touch live systems, secrets, donor private data, production files, financial systems, legal filings, banking systems, payment systems, advertising accounts, trading accounts, or donor communications without the required written approval and human review.

## Allowed Actions

AI tools and agents may perform the following actions when they remain documentation-only and do not expose private data or connect to live systems:

- Read repository documentation.
- Draft new Markdown documentation.
- Edit documentation for clarity, formatting, navigation, consistency, and structure.
- Propose roadmaps, checklists, review workflows, and operating procedures.
- Create branch-based documentation changes for human review.
- Summarize repository content and identify documentation gaps.
- Check links, headings, spelling, formatting, and naming consistency.
- Prepare pull request summaries for documentation-only changes.
- Suggest safe future automation concepts without connecting tools to live systems.
- Add placeholders that clearly state human review is required before operational use.
- Document assumptions when facts are incomplete.
- Separate ministry, foundation, church, business, funding, and operations roles clearly.
- Preserve consistent entity names:
  - Rays of Resilience International Ministries.
  - Rays of Resilience Foundation.
  - Rays of Resilience International Ministries Limited.

## Blocked Actions

AI tools and agents must not perform, initiate, assist with, or automate any of the following actions unless the listed approval level is met. Some actions remain blocked even after approval unless performed directly by authorized humans outside AI tooling.

### Production and Server Boundaries

- No production deployment without written approval.
- No server changes without written approval.
- No infrastructure changes without written approval.
- No hosting changes without written approval.
- No environment variable changes on live systems.
- No production configuration changes.
- No database migrations or direct production database writes.
- No deleting, moving, renaming, overwriting, or replacing production files.
- No restarting, stopping, scaling, or modifying live services.
- No connecting tools, scripts, agents, or automations to live systems without written approval.

### Secrets and Credentials

- No API key handling.
- No password handling.
- No token handling.
- No private key handling.
- No service account credential handling.
- No banking credential handling.
- No payment processor credential handling.
- No email account credential handling.
- No hosting credential handling.
- No credential creation, storage, printing, movement, rotation, testing, or validation by AI tools.
- No committing secrets or secret-like values to the repository.

If a secret or credential is discovered, AI tools must stop work, avoid repeating the value, avoid storing it in logs or summaries, and escalate to the emergency stop process.

### Donor, Partner, Child, and Private Data

- No donor data exposure.
- No donor private data collection, copying, processing, exporting, summarizing, or publishing.
- No partner private data exposure.
- No child private data exposure.
- No uploading private records into AI tools.
- No donor payment history exposure.
- No private contact list exposure.
- No public release of sensitive ministry, orphanage, family, child, donor, or partner details.

Use anonymized or fictional examples when documentation needs sample data.

### Legal, Compliance, and Filings

- No legal filing changes without attorney review.
- No corporate registration changes without attorney review.
- No nonprofit, charity, tax, compliance, or regulatory filing changes without attorney review.
- No changes to governance documents, legal representations, tax positions, donor tax language, or compliance commitments without attorney review.
- No AI-generated legal advice may be treated as final guidance.

AI tools may draft questions, checklists, or non-final notes for attorney review when clearly labeled as drafts.

### Financial, Banking, Ads, Trading, and Payment Actions

- No financial actions.
- No banking actions.
- No payment actions.
- No payment processor setup, testing, transaction creation, refunding, reconciliation, payout, or account changes.
- No advertising account setup, budget changes, campaign launches, campaign edits, audience uploads, or spend actions.
- No trading actions.
- No investment account actions.
- No cryptocurrency wallet actions.
- No loan, grant, payroll, tax payment, vendor payment, or budget commitment execution.
- No changes to prices, checkout flows, donation flows, payment links, bank details, or payout settings.

AI tools may draft documentation about proposed processes, but humans must review and execute any actual financial, banking, ads, trading, or payment work outside AI tooling.

### Donor and Partner Communications

- No automated emails to donors or partners.
- No automated text messages, direct messages, phone calls, newsletters, or outreach campaigns to donors or partners.
- No mailing list imports or exports.
- No AI agent may send messages as Rays of Resilience International Ministries, Rays of Resilience Foundation, Rays of Resilience International Ministries Limited, Roman Corona, Mawazi Azalwa, Pastor Ronald, or any team member.
- No donor segmentation or targeted outreach automation using private donor data.

AI tools may draft message templates for human review only. Drafts must not be sent automatically.

### Website and Public Content Boundaries

- No live website changes without review.
- No public page publishing without review.
- No domain, DNS, SSL, analytics, tag manager, form, checkout, donation, or hosting changes without approval.
- No changing donor-facing claims, legal statements, tax statements, financial claims, or payment instructions without review.
- No connecting website forms to live email, donor, CRM, payment, or database systems without approval.

### Repository and Automation Boundaries

- No adding deployment workflows that can write to production.
- No modifying CI/CD, release, deployment, hosting, or infrastructure automation without approval.
- No creating scripts that call live services.
- No adding third-party integrations that require secrets.
- No installing or configuring tools to access live ministry, donor, payment, banking, email, hosting, website, or production systems.
- No destructive file operations outside reviewed documentation changes.

## Approval Levels

Approval must be written, specific, and recorded in an audit-friendly place such as an issue, pull request, approved task document, or signed communication. Vague approval does not authorize sensitive action.

### Level 0: Documentation-Only Work

Allowed without special approval when normal repository rules are followed:

- Markdown documentation edits.
- Documentation navigation updates.
- Documentation review checklists.
- Planning documents.
- Naming consistency cleanup.
- Non-operational examples using fictional data.

Requirements:

- Human review before merge when possible.
- No secrets.
- No production changes.
- No live integrations.
- No donor private data.

### Level 1: Human Review Required

Requires review by Roman or a designated reviewer before publication or merge:

- Donor-facing wording.
- Public website copy drafts.
- Partner-facing communication drafts.
- Ministry role descriptions.
- Operational process documents.
- Funding system documentation.
- Business platform documentation.
- Any statement that could create public expectations or commitments.

### Level 2: Written Approval Required Before Work Begins

Requires explicit written approval before drafting or changing implementation-oriented material:

- Live website change planning.
- Server, hosting, DNS, domain, analytics, email, CRM, or form integration planning.
- Automation plans involving external systems.
- Payment, donor management, banking, ads, or financial workflow planning.
- Changes to deployment, infrastructure, or production-related configuration.

AI tools still must not execute the live changes. Approval only permits planning or documentation unless the approval explicitly states a broader scope and the action is safe for AI involvement.

### Level 3: Expert Review Required

Requires Roman's written approval plus review by a qualified expert before action:

- Legal filing changes: attorney review required.
- Tax or compliance statements: attorney, CPA, or qualified compliance review required.
- Financial controls, banking setup, accounting policy, or payment processor changes: qualified financial or compliance review required.
- Child privacy, safeguarding, data protection, or sensitive records processes: qualified safeguarding, privacy, or legal review required.

AI tools may prepare drafts and questions for expert review only.

### Level 4: Human-Only Execution

The following actions must be performed by authorized humans outside AI tooling, even if AI helps draft a checklist:

- Entering, rotating, or validating credentials.
- Accessing donor private data.
- Accessing banking systems.
- Accessing payment processors.
- Sending donor or partner communications.
- Filing legal or regulatory documents.
- Deploying production systems.
- Changing live servers, production databases, DNS, domains, or hosting.
- Deleting production files.
- Launching ads, making trades, or moving funds.

## Emergency Stop Rules

AI tools and agents must stop immediately if any task, file, prompt, output, or requested action includes or appears to require:

- API keys, passwords, tokens, private keys, credentials, or service account files.
- Donor private data, donor payment data, private contact lists, or private partner data.
- Child private data or sensitive family records.
- Production deployment.
- Server, hosting, DNS, database, email, payment, banking, ads, trading, or live website access.
- Automated donor or partner outreach.
- Legal filing changes or legal commitments.
- Financial transactions, refunds, payouts, purchases, ad spend, trading, or payment processing.
- Deleting production files.
- Connecting any AI tool or automation to a live system.
- Any uncertainty about whether an action touches production, secrets, private data, legal, financial, donor, payment, or live operational systems.

When an emergency stop is triggered, the AI tool or agent must:

1. Stop the sensitive action immediately.
2. Do not print, copy, summarize, transform, or store the sensitive value or private data.
3. Preserve current repository work only if it is safe and documentation-only.
4. Report the stop condition in general terms without exposing sensitive details.
5. Request human review before continuing.
6. Recommend credential rotation or incident review when a secret may have been exposed.
7. Do not resume until written approval and a safe path are provided.

## Rollback Requirements

Every approved change that could affect public documentation, donor clarity, website content, workflows, integrations, or operations must have a rollback plan before execution.

For documentation-only changes, rollback requirements are:

- Work in a branch when possible.
- Use pull requests for review when possible.
- Keep commits focused and descriptive.
- Confirm changed files before commit.
- Revert by commit revert or restoring the previous file version if needed.
- Document what changed and what did not change in the pull request summary.

For any approved non-documentation planning that may later affect systems, rollback planning must include:

- Owner responsible for rollback.
- Exact system or file affected.
- Backup or restore point requirement.
- Steps to return to the previous known-good state.
- Communication plan for affected people.
- Verification checks after rollback.
- Incident notes if private data, production systems, or donor-facing systems were involved.

AI tools must not execute production rollback actions. They may draft rollback checklists for authorized humans.

## Audit Log Requirements

All AI-assisted work should leave a clear audit trail. The record should make it possible for a human reviewer to understand what was changed, why it was changed, who requested it, and what safety checks were performed.

For documentation-only repository work, record:

- Files changed.
- Summary of changes.
- Confirmation that the work is documentation-only.
- Confirmation that no secrets were added.
- Confirmation that no production systems were changed.
- Confirmation that no live integrations were connected.
- Confirmation that no donor private data was exposed.
- Tests or checks run, such as formatting review, link review, or repository status checks.
- Commit hash or pull request reference when available.

For any approved planning involving sensitive areas, also record:

- Written approval reference.
- Approval level.
- Reviewer or expert required.
- Scope of approval.
- Explicit list of actions not authorized.
- Risk notes.
- Rollback plan location.
- Final human decision.

Audit logs must not include secrets, credentials, donor private data, child private data, banking data, payment data, private contact lists, or other sensitive records.

## Minimum Review Checklist

Before any AI-assisted change is merged, published, or used operationally, confirm:

- [ ] The change is documentation-only, or the correct approval level is recorded.
- [ ] No secrets, credentials, or secret-like values were added.
- [ ] No donor private data, child private data, payment data, banking data, or private contact lists were exposed.
- [ ] No production deployment was performed.
- [ ] No server, hosting, DNS, database, payment, banking, ads, trading, email, or live website changes were made.
- [ ] No live tool connection or automation was added.
- [ ] No automated donor or partner communications were sent.
- [ ] No legal filing, tax, compliance, or financial commitment was changed without required expert review.
- [ ] Entity names remain consistent.
- [ ] Ministry, foundation, church, business, funding, and operations roles remain clearly separated.
- [ ] Rollback path is clear.
- [ ] Audit notes are complete and do not contain sensitive data.

## Current Authorization Status

Current status: documentation-only.

This document does not authorize:

- Production deployment.
- Server changes.
- API key or credential handling.
- Donor data exposure.
- Legal filing changes.
- Financial, banking, ads, trading, or payment actions.
- Automated emails to donors or partners.
- Deleting production files.
- Live website changes.
- Connecting tools to live systems.
