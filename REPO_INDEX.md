# Repository Index

## Purpose

This index explains the purpose and safe use of the major repository guidance files that already exist in the Rays of Resilience documentation repository.

The index is documentation-only. It does not authorize deployment, production changes, secret handling, live integrations, financial action, legal action, or operational commitments.

## Repository Safety Rules

All readers and AI assistants should follow these rules when using the files listed in this index:

1. Keep work documentation-only unless Roman gives explicit written approval for a wider scope.
2. Do not place secrets, passwords, tokens, API keys, donor private data, child private data, payment data, banking data, hosting credentials, email credentials, or service account files in any repository document.
3. Do not use this repository to deploy systems, modify production systems, connect live services, process payments, send live email, change hosting, change donor systems, or operate ministry systems.
4. Keep the legal and operating roles clear:
   - Rays of Resilience International Ministries is the parent ministry structure.
   - Rays of Resilience Foundation is the child support and community support structure.
   - Rays of Resilience International Ministries Limited is the Uganda operating entity.
5. Escalate legal, financial, tax, compliance, donor-facing, child-safety, investment, public-communications, and operational commitment questions for human review.

## Major File Guide

### `AGENTS.md`

**What it controls**

- The top-level agent instructions for this repository.
- The main entry points that AI assistants and contributors should read first.
- Core entity naming rules for Rays of Resilience International Ministries, Rays of Resilience Foundation, and Rays of Resilience International Ministries Limited.
- The repository-wide documentation-only safety boundary for agent work.

**When to use it**

- At the start of any AI-assisted repository task.
- Before editing documentation.
- When checking whether a requested task is inside the repository's permitted scope.
- When confirming correct entity names and high-level output priorities.

**Who should read it**

- AI assistants working in the repository.
- Human contributors preparing documentation updates.
- Reviewers checking whether an edit followed repository rules.
- Anyone onboarding to the repository structure.

**What must not be placed inside it**

- Secrets, credentials, tokens, passwords, private keys, donor private data, child private data, payment data, banking data, or service account details.
- Deployment commands, production access steps, live integration instructions, or infrastructure credentials.
- Final legal, financial, tax, compliance, donor, or public-communications commitments.
- Detailed operational procedures for live systems.

### `AGENT_MAP.md`

**What it controls**

- Future AI and automation agent roles for the repository.
- Allowed work, restricted work, required inputs, expected outputs, approval requirements, and stop conditions for each agent role.
- Shared global rules and safety stops for all agents.
- Recommended workflow and review checklist for agent-assisted documentation work.

**When to use it**

- When deciding which agent role should handle a task.
- When defining or reviewing future agent responsibilities.
- When checking whether an agent is being asked to exceed its authority.
- When preparing an agent handoff or review packet.

**Who should read it**

- Roman and trusted collaborators designing AI workflows.
- AI assistants that route, draft, edit, or review documentation.
- Reviewers validating that agent responsibilities stay documentation-first.
- Future system designers planning safe automation.

**What must not be placed inside it**

- Working credentials, API keys, passwords, access tokens, private donor records, private child records, banking data, or payment data.
- Instructions that grant live production access or bypass human approval.
- Legal authority, financial authority, investment authority, donor approval authority, or ministry leadership authority for an AI agent.
- Executable automation code or live service configuration.

### `COMMAND_ROUTER.md`

**What it controls**

- How commands, requests, and tasks should move between ChatGPT, Codex, Claude Code, OpenClaw, Jarvis, and human reviewers.
- Routing principles for choosing the smallest safe tool for a task.
- Standard documentation flow, review-only flow, multi-tool flow, routing table, command formats, escalation rules, and stop conditions.
- Entity naming rules and repository entry points for routed work.

**When to use it**

- Before assigning a task to a tool or agent.
- When converting a human request into a safe task brief.
- When deciding whether work belongs in planning, drafting, repository editing, review, or escalation.
- When documenting handoffs between tools.

**Who should read it**

- Human coordinators routing work.
- AI assistants preparing task briefs or pull request work.
- Reviewers checking whether the correct tool was used.
- Future orchestration systems that need safe routing rules.

**What must not be placed inside it**

- Secrets, credentials, private data, production endpoints, or live access instructions.
- Commands that deploy, mutate production systems, process payments, send live emails, change hosting, or write to donor systems.
- Routing rules that remove human review from legal, financial, donor-facing, compliance, child-safety, investment, or public-communications decisions.
- Unapproved automation that executes live tasks.

### `TASK_INTAKE.md`

**What it controls**

- How tasks are accepted, reviewed, prioritized, escalated, or stopped.
- Approved documentation-only task categories and restricted task categories.
- Documentation-only rules, human approval checkpoints, escalation rules, emergency stop conditions, and task priority levels.
- Safe and blocked command examples plus an intake checklist.

**When to use it**

- Before starting a new task.
- When deciding whether a request is safe, restricted, blocked, or needs human approval.
- When prioritizing documentation work.
- When writing an intake checklist for future work.

**Who should read it**

- Anyone submitting or accepting repository tasks.
- AI assistants before beginning work.
- Reviewers checking scope and priority.
- Human coordinators deciding whether to approve, defer, or stop a request.

**What must not be placed inside it**

- Real secrets, private personal records, donor private data, child private data, payment information, banking details, or login information.
- Live operational tickets that require production access.
- Instructions to bypass approvals, skip review, or continue after a stop condition.
- Final commitments about legal, financial, tax, donor, employment, public, or operational matters.

### `SYSTEM_BOUNDARIES.md`

**What it controls**

- The safety boundaries for AI tools and agents in the repository.
- Allowed actions, blocked actions, approval levels, emergency stop rules, rollback requirements, audit log requirements, and minimum review checklist.
- Clear separation between documentation work and production, server, secrets, donor, legal, financial, public content, repository automation, and live operations boundaries.

**When to use it**

- When a task might touch risk, authority, private data, production systems, public content, finances, donor communications, legal topics, or compliance topics.
- Before approving work that may exceed documentation-only scope.
- During review when checking whether a proposed change crossed a boundary.
- When writing rollback or audit requirements for future safe workflows.

**Who should read it**

- AI assistants and human contributors.
- Reviewers responsible for safety and scope.
- Roman and delegated approvers.
- Future automation designers and system operators.

**What must not be placed inside it**

- Credentials, keys, tokens, passwords, private donor or child data, payment data, banking data, or access details.
- Exact production access procedures, deployment runbooks, or server mutation steps.
- Exceptions that authorize AI tools to perform human-only execution without written approval and review.
- Sensitive legal, financial, or compliance records that should live outside this documentation repository.

### `WORKFLOW_MAP.md`

**What it controls**

- The workflow model for AI-assisted planning, documentation, review, testing, approval, blocked work, emergency stops, and future production workflow concepts.
- Tool responsibilities for ChatGPT, Codex, Claude Code, OpenClaw, Jarvis, and any future approved execution layer.
- Handoff summary format and current safe operating status.

**When to use it**

- When planning the sequence of work for a documentation change.
- When preparing a handoff between planning, editing, review, and approval.
- When documenting test and validation expectations for documentation-only changes.
- When identifying whether a workflow should stop or escalate.

**Who should read it**

- Human coordinators managing repository work.
- AI assistants involved in multi-step workflows.
- Reviewers checking process quality.
- Future automation planners designing safe handoffs.

**What must not be placed inside it**

- Live production workflow credentials or executable deployment steps.
- Secrets, private data, payment details, banking details, donor records, child records, or access tokens.
- Instructions that convert future production concepts into current authorization.
- Approval shortcuts for sensitive, public, legal, financial, donor, child-safety, investment, or operational workflows.

### `MEMORY_POLICY.md`

**What it controls**

- What AI tools and repository documentation may remember, summarize, archive, delete, review, audit, and publish.
- Rules for donor data, legal data, financial data, ministry operations memory, project documentation memory, temporary memory, and public documentation standards.
- Memory file standards and enforcement rules.

**When to use it**

- Before adding information to `memory/` files or other long-term documentation.
- When deciding whether a fact, note, summary, or record is safe to keep.
- When reviewing whether repository memory contains private, sensitive, stale, or inappropriate data.
- When planning deletion, archiving, or audit processes.

**Who should read it**

- AI assistants that summarize or store repository context.
- Human contributors maintaining memory or project notes.
- Reviewers checking privacy and safety.
- Future automation designers working with context persistence.

**What must not be placed inside it**

- Actual private memory records, donor profiles, child records, passwords, API keys, payment details, banking details, or credentials.
- Sensitive case details, legal files, financial records, or personal data.
- Rules that permit indefinite storage of private data without review.
- Live system connection details or production access instructions.

### `APPROVAL_MATRIX.md`

**What it controls**

- Approval levels for AI-assisted work.
- The difference between safe drafting, documentation PRs, code changes, website changes, sensitive donor/legal/financial/server work, and blocked actions.
- Stop conditions, rollback requirements, audit log requirements, and escalation rules.

**When to use it**

- Before approving a task, pull request, workflow, or future automation step.
- When deciding whether a request is Level 0, Level 1, Level 2, Level 3, Level 4, or Level 5.
- During review of tasks that may affect public messaging, legal matters, finances, donor communications, websites, servers, credentials, or production systems.
- When documenting what approval is required before work begins.

**Who should read it**

- Roman and delegated approvers.
- AI assistants preparing work plans or pull requests.
- Human reviewers checking risk level.
- Contributors requesting work that may exceed normal documentation updates.

**What must not be placed inside it**

- Written approvals containing secrets, passwords, tokens, financial account details, donor private data, child private data, or private legal records.
- Instructions that allow sensitive or blocked work without the required reviewers.
- Production deployment steps, server credentials, payment processing instructions, or live system access procedures.
- Final legal, tax, financial, donor, employment, investment, or compliance determinations.

### `docs/overview/ai-tooling-roadmap.md`

**What it controls**

- The roadmap for safe AI tooling in the repository.
- Current repository role, safety rules, tool roles, Claude Code connection guidance, Codex responsibilities, connection model, repository permission recommendations, documentation workflow, milestones, PR checklist, and stop conditions.
- Future planning boundaries for orchestration and automation without connecting live systems.

**When to use it**

- Before AI-assisted repository work.
- When onboarding ChatGPT, Claude Code, Codex, or future AI tools.
- When planning documentation guardrails, tool onboarding notes, review checklists, or optional automation concepts.
- When confirming the repository remains documentation-first and safe for future automation planning.

**Who should read it**

- AI assistants working in this repository.
- Human contributors and documentation reviewers.
- Roman and trusted collaborators evaluating AI tooling.
- Future automation planners and tool administrators.

**What must not be placed inside it**

- API keys, model keys, service tokens, passwords, private data, donor records, child records, payment data, banking data, or service account files.
- Live deployment instructions, production credentials, live automation triggers, or external system write instructions.
- Tool permissions that bypass branch review, human approval, or safety boundaries.
- Operational commitments that have not been reviewed and approved by the appropriate human authority.

## How to Use This Index

1. Start with `AGENTS.md` for global repository rules.
2. Use `docs/overview/ai-tooling-roadmap.md` before AI-assisted work.
3. Use `TASK_INTAKE.md` to classify the request.
4. Use `APPROVAL_MATRIX.md` to confirm the required approval level.
5. Use `SYSTEM_BOUNDARIES.md` when risk, authority, data, production, or public-facing impact is possible.
6. Use `COMMAND_ROUTER.md` to route the task to the correct tool or agent.
7. Use `AGENT_MAP.md` to confirm agent roles and stop conditions.
8. Use `WORKFLOW_MAP.md` to sequence planning, editing, review, validation, approval, and handoff.
9. Use `MEMORY_POLICY.md` before recording or retaining information for future context.

## Index Maintenance Rules

- Keep this file focused on repository navigation and safe use of guidance documents.
- Update this index when a major guidance file is added, renamed, split, or retired.
- Do not add secrets, production instructions, live system details, or sensitive records to this index.
- Do not use this index as a substitute for human review where another policy requires review or approval.
