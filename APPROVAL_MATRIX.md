# AI-Assisted Work Approval Matrix

## Purpose

This approval matrix defines approval levels for AI-assisted work in the Rays of Resilience documentation repository.

It protects Rays of Resilience International Ministries, Rays of Resilience Foundation, and Rays of Resilience International Ministries Limited by keeping documentation, code, website, donor, legal, financial, credential, and production work clearly separated.

## Core Safety Rules

- This repository is documentation-first.
- No secrets may be requested, stored, printed, committed, or moved into repository files.
- No deployment is authorized by this matrix.
- No production system changes are authorized by this matrix.
- Written approval must be specific to the task, scope, reviewer, and rollback plan.
- When a task could fit more than one level, use the higher approval level.
- If the approval level is unclear, stop and request human review before continuing.

## Approval Levels

| Level | Scope | AI action allowed | Review required | Examples |
| --- | --- | --- | --- | --- |
| Level 0 | Documentation-only, safe to draft | Draft locally or in chat without changing repository files | Self-check by the person requesting the draft | Drafting a policy outline, summarizing an existing document, preparing wording options, proposing a table of contents, creating a non-committed checklist |
| Level 1 | Repository documentation updates, PR required | Edit Markdown documentation in a branch and open a pull request | Roman Corona or a delegated documentation reviewer | Updating `docs/overview` files, adding a new planning document, fixing Markdown formatting, correcting internal documentation links, adding clarification notes |
| Level 2 | Code changes, review required | Prepare code changes only after approval to work beyond documentation | Roman Corona plus a technical reviewer | Adding scripts, changing repository tooling, modifying tests, changing code examples that could be executed, adding automation that runs locally only |
| Level 3 | Website changes, approval required | Prepare website changes only after explicit approval; no deployment | Roman Corona plus website owner or technical reviewer | Editing website copy, changing website styling, updating public pages, changing forms, changing public navigation, preparing but not deploying website updates |
| Level 4 | Donor, legal, financial, ads, trading, server, or credential-related work, written approval required | Planning or drafting only unless written approval defines exact permitted action | Roman Corona plus the appropriate responsible reviewer, such as legal, finance, donor communications, advertising, trading, server, or security reviewer | Drafting donor-facing commitments, changing donation language, preparing legal or tax wording, editing ads, touching trading-related material, changing server configuration, handling credential-related instructions |
| Level 5 | Blocked actions unless separately approved | Do not perform the action in this repository or through AI tools unless separate written approval and safety documentation exist first | Roman Corona plus all required domain reviewers before any work begins | Deploying to production, accessing live donor systems, handling passwords or API keys, processing payments, moving funds, making trades, changing DNS, changing hosting production settings, sending bulk emails, connecting live automations |

## Level 0: Documentation-Only, Safe to Draft

Level 0 work is safe exploratory drafting that does not modify repository files and does not create operational commitments.

Examples:

- Drafting an outline for a future policy.
- Summarizing existing Rays of Resilience documentation.
- Preparing suggested wording for human review.
- Creating a checklist in chat before any file is changed.
- Identifying missing documentation areas.

Reviewer:

- The person requesting the draft reviews the output before it is used.
- Roman Corona reviews if the draft affects organization structure, public messaging, donor clarity, or commitments.

Stop conditions:

- The draft starts making promises, legal claims, donor commitments, financial commitments, or operational commitments.
- The draft requires facts that are not documented.
- The draft requires private data, credentials, production access, or external system access.

Rollback requirements:

- No repository rollback is required because no files are changed.
- If inaccurate text was copied elsewhere, remove or correct it and record the correction in the relevant work notes.

Audit log requirements:

- Keep the prompt, date, requester, purpose, assumptions, and final draft when the draft may influence future documentation or decisions.

## Level 1: Repository Documentation Updates, PR Required

Level 1 work updates repository documentation only. It must remain within Markdown and documentation files unless a human explicitly approves a higher level.

Examples:

- Adding this approval matrix.
- Updating overview documentation.
- Fixing broken documentation links.
- Clarifying ministry, foundation, church, business, or leadership roles.
- Adding documentation-only review checklists.

Reviewer:

- Roman Corona or a delegated documentation reviewer reviews the pull request.
- Additional ministry, foundation, business, or leadership reviewers should review if their area is described.

Stop conditions:

- The change adds secrets, credentials, private donor data, payment data, or personal sensitive data.
- The change creates legal, tax, donor, financial, fundraising, employment, or operational commitments.
- The change includes deployment steps, production instructions, live integrations, scripts, code, or infrastructure settings.
- The change blurs the roles of Rays of Resilience International Ministries, Rays of Resilience Foundation, or Rays of Resilience International Ministries Limited.

Rollback requirements:

- Revert the documentation commit or open a correcting pull request.
- If a public statement was copied from the documentation before correction, remove or correct the public statement.
- Record what was changed, why it was reverted, and who approved the rollback.

Audit log requirements:

- Keep the branch name, pull request link or identifier, reviewer, approval date, files changed, summary of change, and confirmation that no secrets, deployment, production changes, or live integrations were included.

## Level 2: Code Changes, Review Required

Level 2 work includes any executable code, scripts, tests, local tooling, generated automation, or configuration that could change behavior inside the repository.

Examples:

- Adding a local documentation lint script.
- Updating a test command.
- Adding a script that checks Markdown links locally.
- Modifying repository automation that does not touch live services.
- Changing code examples that readers may run.

Reviewer:

- Roman Corona reviews the purpose and risk.
- A technical reviewer reviews safety, scope, code behavior, and rollback plan.

Stop conditions:

- The code calls live services, writes to production, requires credentials, sends email, processes payments, changes hosting, accesses donor data, or changes infrastructure.
- The code could run automatically without human review.
- The code changes legal, donor, financial, ads, trading, server, or credential behavior.

Rollback requirements:

- Revert the code commit or disable the code path in a follow-up pull request.
- Remove generated artifacts if they were created by the change.
- Confirm that no external systems were called and no credentials were exposed.

Audit log requirements:

- Keep the pull request, reviewer approvals, commands run, test results, risk notes, affected files, and rollback steps.

## Level 3: Website Changes, Approval Required

Level 3 work includes changes intended for a public or private website, even when the change is only prepared in the repository and not deployed.

Examples:

- Updating website page copy.
- Changing website layout, styling, navigation, or forms.
- Editing donation page wording.
- Preparing a website announcement.
- Changing content that visitors, donors, partners, or volunteers may see.

Reviewer:

- Roman Corona reviews all website changes.
- A website owner, communications reviewer, or technical reviewer reviews public presentation and implementation safety.
- Donor-facing or commitment-related website changes also require Level 4 review.

Stop conditions:

- The work requires deployment, production access, hosting access, DNS access, payment access, donor data, form submission access, email sending, or credentials.
- The work affects donation commitments, legal wording, tax wording, privacy statements, fundraising claims, financial claims, or ads.
- The website change could confuse the separation between ministry, foundation, church, business, and Uganda operating entity roles.

Rollback requirements:

- Revert the website source change or prepare a correcting pull request.
- If deployed later by approved humans, keep a documented path to restore the previous website version.
- Remove or correct copied public content if a draft was used outside the repository by mistake.

Audit log requirements:

- Keep the approval record, screenshots or preview notes when available, pull request, reviewer names, changed pages, deployment status, and rollback plan.

## Level 4: Donor, Legal, Financial, Ads, Trading, Server, or Credential-Related Work, Written Approval Required

Level 4 work is high-risk. AI may only plan, draft, or organize information unless written approval clearly authorizes a specific additional action.

Examples:

- Drafting donor-facing language or donation restrictions.
- Preparing legal, tax, compliance, or registration wording for attorney or professional review.
- Drafting grant, fundraising, sponsorship, or financial reporting language.
- Preparing advertising copy or audience notes.
- Discussing trading systems, investment actions, or fund movement.
- Planning server changes, DNS changes, hosting changes, environment variables, or credential rotation.
- Writing instructions about credentials without exposing the credential values.

Reviewer:

- Roman Corona must provide written approval.
- The relevant domain reviewer must also review, such as legal counsel, tax advisor, finance reviewer, donor communications reviewer, advertising reviewer, trading reviewer, server administrator, or security reviewer.

Stop conditions:

- A credential value, private donor record, payment record, bank detail, tax identifier, private legal document, private account detail, or other sensitive data is requested or exposed.
- The task would move money, place trades, submit ads, change servers, change DNS, alter credentials, send donor communications, submit legal filings, or create binding commitments.
- The reviewer is not identified or written approval is missing.

Rollback requirements:

- Revert repository changes immediately if sensitive or unapproved content is added.
- Rotate any credential that may have been exposed outside the repository process.
- Notify Roman Corona and the appropriate domain reviewer.
- Correct or retract any donor, legal, financial, advertising, trading, server, or credential-related statement that was shared prematurely.

Audit log requirements:

- Keep written approval, scope, reviewer names, approval date, risk classification, files changed, commands run, external systems intentionally not accessed, rollback plan, and final review outcome.
- Do not store secret values in the audit log.

## Level 5: Blocked Actions Unless Separately Approved

Level 5 actions are blocked by default. They require separate written approval, a dedicated safety plan, identified reviewers, rollback steps, and explicit confirmation that the work may proceed.

Examples:

- Deploying to production.
- Accessing, exporting, editing, or importing live donor records.
- Handling passwords, API keys, access tokens, service account files, private keys, or production environment files.
- Processing donations, payments, refunds, payroll, bank transfers, or fund movements.
- Placing trades or connecting trading automations.
- Changing production hosting, DNS, servers, databases, email sending systems, or payment systems.
- Sending bulk donor, volunteer, marketing, or ministry emails.
- Connecting AI tools to live ministry, donor, payment, banking, website, email, hosting, or operations systems.

Reviewer:

- Roman Corona must separately approve the specific action in writing.
- All required domain reviewers must approve before work begins.
- A technical or security reviewer must approve any system access, credential, deployment, server, or integration plan.

Stop conditions:

- Any approval is missing, vague, expired, or not specific to the action.
- The work requires a secret to be pasted into chat, committed to the repository, or exposed in logs.
- A rollback plan, audit plan, or responsible human operator is missing.
- The action could affect production users, donors, funds, public websites, live systems, or legal obligations without direct human control.

Rollback requirements:

- Stop the action immediately.
- Restore the last known safe state using the approved rollback plan.
- Rotate exposed credentials if any exposure is possible.
- Notify Roman Corona, domain reviewers, and affected system owners.
- Document the incident, impact, correction, and prevention steps.

Audit log requirements:

- Keep separate written approval, risk assessment, reviewer approvals, operator name, time window, exact actions approved, commands or manual steps performed, systems touched, rollback result, incident notes if any, and final signoff.
- Never include secret values in the audit log.

## General Stop Conditions

Stop work and request human review immediately if any of the following appear:

- Secrets, credentials, tokens, passwords, private keys, or production environment values.
- Donor private data, payment data, banking data, tax identifiers, or sensitive personal information.
- Legal, tax, compliance, financial, fundraising, donor, advertising, trading, employment, or contractual commitments.
- Production access, deployment steps, hosting access, DNS changes, server changes, live database access, payment systems, banking systems, email sending, or live website administration.
- Unclear ownership between Rays of Resilience International Ministries, Rays of Resilience Foundation, and Rays of Resilience International Ministries Limited.
- A request to bypass review, commit directly to a protected branch, hide a change, skip an audit log, or remove rollback requirements.
- Any instruction that conflicts with repository safety rules, donor clarity, legal structure, or human review requirements.

## General Rollback Requirements

Every non-draft change must have a rollback path before work begins.

Minimum rollback requirements:

- Identify the last known safe version.
- Use version control to revert repository changes when possible.
- Document what was reverted and why.
- Confirm that no secrets were committed or exposed.
- Confirm that no deployment or production change occurred unless separately approved.
- Notify the reviewer responsible for the approval level.
- Create a correcting pull request when a direct revert is not appropriate.

## General Audit Log Requirements

AI-assisted work must be traceable enough for humans to understand what happened and why.

Minimum audit log fields:

- Date of work.
- Requester.
- AI tool or assistant used.
- Approval level.
- Scope of work.
- Files changed.
- Commands or checks run.
- Reviewer or approver.
- Pull request or commit identifier when available.
- Summary of changes.
- Stop conditions checked.
- Rollback plan.
- Confirmation that no secrets, production changes, deployments, or live integrations were included.

Audit logs must not include secret values, private donor records, payment details, banking details, or sensitive personal information.

## Approval Escalation Rule

If a task begins at one level and later touches a higher-risk area, stop the task and escalate to the higher approval level before continuing.

Examples:

- A documentation update becomes Level 4 if it adds donor-facing donation commitments.
- A local script becomes Level 4 or Level 5 if it needs credentials or live server access.
- A website wording update becomes Level 4 if it changes legal, tax, financial, donor, or fundraising claims.
- Any task becomes Level 5 if it requires production deployment, live systems, funds movement, trading, credential handling, or bulk communications.
