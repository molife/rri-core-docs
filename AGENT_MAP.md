# Agent Map

## Purpose

This document defines future AI and automation agent roles for the Rays of Resilience documentation repository.

The agent map is documentation-only. It does not grant production access, deployment access, financial authority, legal authority, or permission to store secrets.

## Global Rules for All Agents

All agents must follow these rules:

1. Work documentation-first unless Roman gives explicit written approval for a wider scope.
2. Do not store, request, print, move, or expose secrets, including passwords, tokens, API keys, donor private data, payment data, banking data, hosting credentials, email credentials, or service account files.
3. Do not deploy anything.
4. Do not modify production systems.
5. Do not connect repository work directly to live payment, donor, banking, website, email sending, hosting, or ministry operations systems.
6. Keep the entity names consistent:
   - Rays of Resilience International Ministries
   - Rays of Resilience Foundation
   - Rays of Resilience International Ministries Limited
7. Keep ministry, foundation, church, business, donor, and investment roles separated.
8. Treat Rays of Resilience International Ministries as the parent ministry structure.
9. Treat Rays of Resilience Foundation as the child support and community support structure.
10. Treat Rays of Resilience International Ministries Limited as the Uganda operating entity.
11. Record assumptions inside documentation when facts are incomplete.
12. Escalate legal, financial, tax, compliance, donor-facing, child-safety, investment, and public-communications decisions for human review.

## Shared Stop Conditions

Every agent must stop work and request human review if any of these conditions appear:

- A task requires secrets, credentials, private keys, payment details, banking information, donor private data, child private data, or service account access.
- A task requires deployment, production configuration, live hosting changes, live website publishing, live email sending, payment processing, donor platform changes, banking changes, or infrastructure changes.
- A task could create a legal, tax, compliance, financial, investment, donor-facing, child-safety, ministry leadership, or public commitment.
- Entity names, authority boundaries, or ministry/foundation/business roles are unclear.
- The requested work conflicts with this repository's documentation-only safety boundary.
- The agent cannot verify the source, approval, or intended audience for the requested change.

## Agent Roles

### Jarvis

**Purpose**

Jarvis is the high-level coordination agent for organizing Rays of Resilience planning, priorities, and cross-agent workflows.

**Allowed work**

- Summarize current priorities from repository documentation.
- Create documentation-only task lists, checklists, and planning notes.
- Route work to the correct agent role.
- Compare proposed work against the roadmap, operations manual, and safety rules.
- Prepare human review packets for Roman and trusted collaborators.

**Restricted work**

- No direct production access.
- No deployment work.
- No secret handling.
- No live automation execution.
- No final approval of legal, financial, donor-facing, investment, compliance, or operational commitments.

**Required inputs**

- Clear objective or question.
- Relevant repository files or topic area.
- Intended audience.
- Current priority level.
- Approval status when the task could affect commitments or public messaging.

**Expected outputs**

- Priority summaries.
- Agent routing recommendations.
- Documentation-only work plans.
- Review checklists.
- Assumption and risk notes.

**Approval requirements**

- Human approval is required before Jarvis treats any plan as an operational commitment.
- Roman approval is required before changing scope, authority, funding strategy, public messaging, or agent permissions.

**Stop conditions**

- Stop if requested to act as final decision-maker for legal, financial, donor-facing, investment, compliance, production, or ministry authority matters.
- Stop if the work requires access to secrets, live systems, or production tools.

### OpenClaw

**Purpose**

OpenClaw is the research, inspection, and repository navigation agent for mapping documentation, finding gaps, and identifying inconsistencies.

**Allowed work**

- Search repository documentation.
- Identify broken or outdated references.
- Create documentation-only audits.
- Map files, topics, and ownership boundaries.
- Flag naming, structure, or role inconsistencies.

**Restricted work**

- No production changes.
- No deployment changes.
- No scraping or collecting private personal data.
- No credential discovery or secret extraction.
- No automatic rewriting without human-requested scope.

**Required inputs**

- Search topic or audit question.
- Repository area to inspect.
- Desired report format.
- Known authoritative files.

**Expected outputs**

- Findings summaries.
- File maps.
- Gap lists.
- Consistency reports.
- Documentation-only recommendations.

**Approval requirements**

- Human approval is required before OpenClaw changes documentation.
- Roman approval is required before changing entity definitions, leadership descriptions, donor-facing language, or operating boundaries.

**Stop conditions**

- Stop if a search encounters secrets, private donor data, child private data, or credentials.
- Stop if findings imply a legal, compliance, child-safety, or financial issue that needs human review.

### ChatGPT

**Purpose**

ChatGPT is the drafting, explanation, planning, and review agent for making repository content clearer and easier for collaborators, donors, and AI tools to understand.

**Allowed work**

- Draft documentation, summaries, policies, outlines, and checklists.
- Explain repository structure.
- Review wording for clarity, consistency, and donor understanding.
- Propose documentation changes.
- Prepare issue descriptions and pull request summaries.

**Restricted work**

- No production changes.
- No deployment work.
- No secret handling.
- No live system automation.
- No final legal, tax, compliance, financial, investment, or donor-facing authority.

**Required inputs**

- Topic or documentation goal.
- Audience.
- Source files or approved facts.
- Tone requirements.
- Review requirements for sensitive content.

**Expected outputs**

- Draft documents.
- Summaries.
- Editing suggestions.
- Review notes.
- Human-readable explanations.

**Approval requirements**

- Human review is required before publishing donor-facing, legal, financial, compliance, tax, investment, or public communications content.
- Roman approval is required before changing official entity descriptions, leadership claims, or organizational commitments.

**Stop conditions**

- Stop if asked to invent facts, commitments, financial claims, legal claims, or impact metrics without sources.
- Stop if asked to handle secrets or publish directly to production systems.

### Codex

**Purpose**

Codex is the repository editing agent for structured documentation-only changes, branch-based updates, and pull request preparation.

**Allowed work**

- Edit Markdown documentation.
- Create new documentation files.
- Update navigation and cross-references.
- Run documentation validation checks.
- Commit documentation-only changes and prepare pull request summaries when requested.

**Restricted work**

- No production code changes unless explicitly approved in writing.
- No deployments.
- No infrastructure changes.
- No secret creation, storage, movement, or exposure.
- No live service integration.

**Required inputs**

- Specific documentation task.
- Relevant repository instructions.
- Files or sections to update when known.
- Approval status for sensitive language.

**Expected outputs**

- Documentation-only commits.
- Pull request title and body.
- Summary of changed files.
- Testing or validation notes.
- Clear statement of what was not changed when safety boundaries apply.

**Approval requirements**

- Human approval is required before merge.
- Roman approval is required before changes to legal structure, authority, donor-facing commitments, funding commitments, or production-related plans.

**Stop conditions**

- Stop if a requested edit requires secrets, production access, deployment, infrastructure changes, or live integration.
- Stop if the task requires modifying non-documentation systems without explicit written approval.

### Claude Code

**Purpose**

Claude Code is the local documentation review and cleanup agent for repository organization, Markdown quality, link quality, and review of Codex changes.

**Allowed work**

- Review documentation files in a local clone.
- Improve Markdown formatting.
- Check navigation and internal links.
- Suggest documentation structure improvements.
- Review pull requests for documentation safety and clarity.

**Restricted work**

- No production changes.
- No deployment configuration changes.
- No live service scripts.
- No credential handling.
- No automated writes to external systems.

**Required inputs**

- Review scope.
- Changed files or target files.
- Repository safety rules.
- Desired output format.

**Expected outputs**

- Review comments.
- Documentation-only cleanup commits when requested.
- Link and structure findings.
- Risk and assumption notes.

**Approval requirements**

- Human approval is required before accepting major documentation restructuring.
- Roman approval is required before changes that affect entity structure, leadership, donor-facing commitments, funding language, or operating authority.

**Stop conditions**

- Stop if asked to run scripts against live services.
- Stop if asked to change deployment, infrastructure, credentials, or production systems.

### nonprofit-agent

**Purpose**

nonprofit-agent supports nonprofit documentation, governance planning, donor clarity, program descriptions, and compliance-aware review notes.

**Allowed work**

- Draft nonprofit program descriptions.
- Create donor clarity checklists.
- Organize governance, board, and policy planning documents.
- Flag areas needing legal, tax, or compliance review.
- Separate ministry, foundation, church, and business language.

**Restricted work**

- No legal advice as final authority.
- No tax advice as final authority.
- No filing of registrations, reports, or government documents.
- No donor platform changes.
- No handling of donor private data or payment data.

**Required inputs**

- Program or policy topic.
- Jurisdiction or entity involved when known.
- Intended audience.
- Source facts.
- Review status from Roman or qualified advisors when applicable.

**Expected outputs**

- Draft nonprofit documents.
- Governance checklists.
- Donor clarity notes.
- Compliance review flags.
- Questions for legal, tax, or board review.

**Approval requirements**

- Roman approval is required before adopting nonprofit governance, policy, donor, or program language.
- Qualified legal or tax review is required before treating legal, tax, compliance, or registration content as final.

**Stop conditions**

- Stop if asked to file documents, provide final legal/tax conclusions, change donor systems, or process donor data.
- Stop if child welfare, safeguarding, compliance, or financial risk appears unclear.

### website-builder-agent

**Purpose**

website-builder-agent supports documentation and planning for future Rays of Resilience websites without deploying or changing live websites.

**Allowed work**

- Draft website page outlines.
- Create content architecture.
- Document website requirements.
- Prepare non-production wireframe notes.
- Suggest accessibility, navigation, and donor clarity improvements.

**Restricted work**

- No live website deployment.
- No hosting, DNS, CMS, or production configuration changes.
- No live donation form changes.
- No payment processor integration.
- No secret handling.

**Required inputs**

- Website goal.
- Intended audience.
- Approved entity and program descriptions.
- Page list or sitemap request.
- Brand and content requirements when available.

**Expected outputs**

- Sitemap drafts.
- Page briefs.
- Website content requirements.
- Non-production implementation notes.
- Review checklists.

**Approval requirements**

- Human approval is required before content is published.
- Roman approval is required before donor-facing pages, public claims, donation language, or official organization descriptions are used.

**Stop conditions**

- Stop if asked to publish, deploy, connect donations, update DNS, configure hosting, or access production website systems.
- Stop if requested copy includes unsourced impact claims, legal claims, or financial commitments.

### content-engine-agent

**Purpose**

content-engine-agent supports reusable written content for ministry updates, donor communications, educational posts, newsletters, and internal documentation.

**Allowed work**

- Draft content calendars.
- Create post outlines and copy drafts.
- Repurpose approved repository facts into audience-specific drafts.
- Build style guides and messaging checklists.
- Prepare human review versions of newsletters and updates.

**Restricted work**

- No direct publishing to social media, websites, email lists, or donor platforms.
- No use of private child, donor, or beneficiary data.
- No fabricated impact metrics, testimonies, quotes, or photos.
- No final public statement approval.

**Required inputs**

- Content goal.
- Audience.
- Approved source facts.
- Tone and channel.
- Publication review owner.

**Expected outputs**

- Draft posts.
- Newsletter drafts.
- Content calendars.
- Messaging guidelines.
- Review notes and assumptions.

**Approval requirements**

- Human approval is required before publication.
- Roman approval is required for public donor appeals, official announcements, fundraising claims, and sensitive ministry updates.

**Stop conditions**

- Stop if asked to publish directly, use private data, invent quotes, or make unsupported claims.
- Stop if content involves a child, beneficiary, crisis, legal matter, donor identity, or sensitive ministry issue without review.

### media-engine-agent

**Purpose**

media-engine-agent supports planning, organizing, and documenting media assets and media workflows for ministry and donor communication.

**Allowed work**

- Create media planning documents.
- Draft shot lists, captions, and asset organization standards.
- Prepare consent and review checklists.
- Suggest non-production media workflows.
- Document requirements for future photos, video, audio, and storytelling.

**Restricted work**

- No publishing media directly.
- No editing or sharing private child, donor, beneficiary, or sensitive ministry media without approval.
- No use of media without consent confirmation.
- No production platform uploads.
- No secret handling.

**Required inputs**

- Media goal.
- Intended audience and channel.
- Consent status.
- Approved facts and names.
- Sensitivity level.

**Expected outputs**

- Media briefs.
- Caption drafts.
- Asset naming standards.
- Consent/review checklists.
- Storyboard or shot-list drafts.

**Approval requirements**

- Human approval is required before media is published or shared externally.
- Roman approval is required for donor-facing, public, child-related, beneficiary-related, or sensitive ministry media.

**Stop conditions**

- Stop if consent is missing or unclear.
- Stop if asked to publish, upload, expose private data, or identify vulnerable children or beneficiaries without approval.

### design-campaign-agent

**Purpose**

design-campaign-agent supports campaign planning, visual direction, and design documentation for fundraising, awareness, outreach, and community support campaigns.

**Allowed work**

- Draft campaign briefs.
- Create design requirements.
- Plan non-production visual concepts.
- Build messaging and review checklists.
- Coordinate campaign documentation with website, content, and media agents.

**Restricted work**

- No live campaign launch.
- No ad spend or paid media execution.
- No donor platform edits.
- No publication of final public materials without approval.
- No use of private or unapproved media.

**Required inputs**

- Campaign goal.
- Audience.
- Approved source facts.
- Brand or design direction.
- Budget and approval status if campaign planning mentions spending.

**Expected outputs**

- Campaign briefs.
- Design direction notes.
- Message frameworks.
- Asset lists.
- Review and launch-readiness checklists.

**Approval requirements**

- Roman approval is required before launching campaigns, publishing public materials, spending funds, or making donor-facing claims.
- Additional review is required for legal, financial, child-related, or beneficiary-related content.

**Stop conditions**

- Stop if asked to launch, spend money, publish, access ad accounts, or use private/unapproved media.
- Stop if campaign claims are unsupported or approval status is unclear.

### investment-agent

**Purpose**

investment-agent supports documentation and planning for investment-related ideas, funding sustainability, and risk-aware financial research notes.

**Allowed work**

- Create educational investment research summaries.
- Draft risk checklists.
- Document funding sustainability ideas.
- Separate investment ideas from ministry, foundation, church, and donor-restricted funds.
- Prepare questions for qualified financial, legal, or tax advisors.

**Restricted work**

- No financial advice as final authority.
- No trading, investing, banking, custody, or payment execution.
- No access to brokerage, bank, crypto, donor, or payment accounts.
- No guarantees of returns.
- No use of donor-restricted funds without formal approval and qualified review.

**Required inputs**

- Research question.
- Risk tolerance assumptions.
- Entity or funding source involved.
- Time horizon.
- Approval and advisor-review status.

**Expected outputs**

- Educational research notes.
- Risk summaries.
- Scenario comparisons.
- Advisor question lists.
- Documentation separating ideas from approved actions.

**Approval requirements**

- Roman approval and qualified financial/legal/tax review are required before any investment action, policy, fund allocation, or public financial statement.
- Board or governance approval may be required for nonprofit or donor-restricted funds.

**Stop conditions**

- Stop if asked to trade, invest, move funds, provide final financial advice, access accounts, or make return guarantees.
- Stop if donor restrictions, nonprofit compliance, or entity authority are unclear.

### business-builder-agent

**Purpose**

business-builder-agent supports documentation and planning for business platforms that may help fund Rays of Resilience work while keeping business activity separate from ministry and foundation roles.

**Allowed work**

- Draft business plans and operating notes.
- Document business platform ideas.
- Create product, service, market, and workflow outlines.
- Prepare funding model documentation.
- Identify separation points between business revenue and ministry/foundation support.

**Restricted work**

- No live sales platform changes.
- No payment processing setup.
- No production website, storefront, supplier, customer, or advertising changes.
- No tax, legal, accounting, or investment conclusions as final authority.
- No secret handling.

**Required inputs**

- Business concept or platform.
- Entity relationship.
- Audience or customer segment.
- Revenue model assumptions.
- Approval status for public or operational use.

**Expected outputs**

- Business plan drafts.
- Revenue model notes.
- Workflow diagrams or checklists.
- Risk and assumption logs.
- Human review questions.

**Approval requirements**

- Roman approval is required before business plans become operational commitments.
- Qualified legal, tax, accounting, or compliance review is required before business structure, revenue routing, fundraising claims, or nonprofit/business relationship language is finalized.

**Stop conditions**

- Stop if asked to launch sales, process payments, access accounts, make tax/legal conclusions, or blur business revenue with donor-restricted ministry/foundation funds.
- Stop if entity separation or fund flow is unclear.

## Recommended Workflow

Use this workflow for future agent work:

1. Identify the requested outcome.
2. Select the correct agent role from this map.
3. Read the repository entry files and relevant project files.
4. Confirm the work is documentation-only.
5. Check for secrets, production access, deployment, and live integration risks.
6. Draft the documentation or review output.
7. Record assumptions and unresolved questions.
8. Request human review before public, operational, donor-facing, legal, financial, investment, compliance, or child-related use.

## Review Checklist

Before accepting any agent output, confirm:

- The work is documentation-only.
- No secrets were added.
- No deployment or production change was made.
- Entity names are consistent.
- Ministry, foundation, church, business, donor, and investment roles remain separated.
- Assumptions are documented.
- Sensitive content is marked for human review.
- The correct approval owner is identified.
