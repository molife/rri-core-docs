# Command Router

## Purpose

This document defines how commands, requests, and tasks should move between ChatGPT, Codex, Claude Code, OpenClaw, and Jarvis for the Rays of Resilience documentation repository.

The router exists to keep AI-assisted work safe, clear, and documentation-first while supporting the mission and structure of Rays of Resilience International Ministries.

## Repository Scope

This repository documents:

- Rays of Resilience International Ministries as the parent ministry structure.
- Rays of Resilience Foundation as the child support and community support structure.
- Rays of Resilience International Ministries Limited as the Uganda operating entity.
- Ministry work, church development, orphanage support, foundation programs, operations, funding structure, business platforms, priorities, and roadmap planning.

## Safety Boundary

All commands routed through this system must follow these rules:

- Documentation only unless explicit written approval says otherwise.
- No secrets, credentials, passwords, tokens, keys, donor private data, payment data, banking data, or service account files.
- No deployment.
- No production changes.
- No live external system mutation.
- No direct writes to donor, payment, banking, website, email, hosting, or ministry operations systems.
- Human review is required before changes become official operational, legal, financial, donor-facing, tax, compliance, or production commitments.

## Routing Principles

Use the smallest safe tool that can complete the task.

1. Start with context and planning.
2. Route to documentation drafting or repository editing only when needed.
3. Keep implementation separate from approval.
4. Keep commands auditable by recording what was requested, which tool handled it, and what changed.
5. Escalate to a human when a command touches safety, legal, financial, donor, production, or compliance risk.

## Tool Roles

### ChatGPT

Primary role: planning, drafting, explanation, and review.

Use ChatGPT for:

- Translating human goals into clear documentation tasks.
- Drafting outlines, policies, roadmaps, donor clarity language, and review checklists.
- Explaining repository structure and project context.
- Preparing prompts or issue descriptions for Codex, Claude Code, OpenClaw, or Jarvis.
- Reviewing text for consistency with Rays of Resilience naming and structure.

Do not route to ChatGPT for:

- Direct production access.
- Secret handling.
- Deployment execution.
- Live system changes.

Expected output:

- A clear task brief, draft text, checklist, or review note.

### Codex

Primary role: branch-based documentation edits inside the repository.

Use Codex for:

- Creating or editing Markdown documentation.
- Repository-wide documentation search and safe cleanup.
- Navigation updates.
- Documentation-only pull requests.
- Markdown validation and documentation checks.

Do not route to Codex for:

- Production code changes unless explicitly approved in writing.
- Secret creation, storage, movement, or inspection.
- Deployment commands.
- Infrastructure or live integration changes.

Expected output:

- A committed documentation-only branch, a pull request summary, and a test or validation summary.

### Claude Code

Primary role: local documentation review, cleanup, and architecture feedback.

Use Claude Code for:

- Reviewing Codex documentation changes.
- Checking Markdown organization, clarity, and internal consistency.
- Suggesting repository structure improvements.
- Confirming that entity names remain consistent.
- Confirming that ministry, foundation, church, business, and operations roles remain separated.

Do not route to Claude Code for:

- Deployment.
- Production edits.
- Secret handling.
- Live service scripts.
- Operational automation connected to external systems.

Expected output:

- Review comments, documentation-only edits, or architecture notes for human approval.

### OpenClaw

Primary role: future orchestration and command coordination planning.

Use OpenClaw for:

- Planning how documentation tasks should be queued, assigned, and tracked.
- Coordinating safe handoffs between ChatGPT, Codex, Claude Code, Jarvis, and human reviewers.
- Maintaining documentation-only workflow status.
- Creating audit-friendly summaries of command routing decisions.

Do not route to OpenClaw for:

- Production control.
- Live integrations.
- Deployment.
- Secret handling.
- Autonomous changes to donor, payment, banking, website, email, hosting, or ministry operations systems.

Expected output:

- A routing plan, workflow status note, or documentation-only orchestration summary.

### Jarvis

Primary role: high-level assistant, command intake, and human-facing coordination.

Use Jarvis for:

- Receiving human commands and converting them into safe task briefs.
- Asking clarifying questions before work begins when scope is unclear.
- Choosing whether the next step belongs with ChatGPT, Codex, Claude Code, OpenClaw, or a human reviewer.
- Summarizing completed work for Roman or other approved reviewers.
- Tracking decisions that need human approval.

Do not route to Jarvis for:

- Autonomous production actions.
- Secret storage.
- Deployment.
- Direct live system mutation.
- Final approval of legal, financial, donor-facing, tax, compliance, or operational commitments without human review.

Expected output:

- A safe command brief, routing decision, approval request, or completion summary.

## Command Flow

### Standard Documentation Flow

Use this flow for normal documentation work:

1. Human command enters through Jarvis or ChatGPT.
2. Jarvis or ChatGPT converts the command into a safe documentation task brief.
3. Codex makes branch-based documentation-only changes when repository edits are required.
4. Claude Code reviews the change for clarity, structure, naming consistency, and safety boundaries.
5. OpenClaw may track routing status and summarize handoffs if orchestration is being planned.
6. Human reviewer approves, requests revisions, or rejects the change.

### Review-Only Flow

Use this flow when no repository edits are needed:

1. Human asks a question or requests review.
2. ChatGPT or Claude Code reads the relevant documentation.
3. The tool returns a summary, risk note, recommendation, or checklist.
4. Human decides whether future documentation edits are needed.

### Multi-Tool Flow

Use this flow when a request needs planning, editing, and review:

1. ChatGPT drafts the plan.
2. Jarvis confirms the next safe action.
3. Codex edits the repository documentation.
4. Claude Code reviews the pull request.
5. OpenClaw records the workflow status if orchestration tracking is active.
6. Human reviewer makes the final decision.

## Routing Table

| Command Type | Primary Tool | Secondary Tool | Human Review Required |
| --- | --- | --- | --- |
| Draft a new documentation page | ChatGPT | Codex | Yes, before merge |
| Edit Markdown in the repo | Codex | Claude Code | Yes, before merge |
| Review Codex changes | Claude Code | ChatGPT | Yes, for approval |
| Explain repository structure | ChatGPT | Jarvis | No, unless changes are proposed |
| Organize command handoffs | OpenClaw | Jarvis | Yes, before any workflow becomes operational |
| Intake a broad human request | Jarvis | ChatGPT | Yes, if scope affects commitments |
| Check naming consistency | Claude Code | Codex | Yes, if edits are made |
| Create donor-facing wording | ChatGPT | Claude Code | Yes |
| Update legal, tax, compliance, or financial language | Human reviewer | ChatGPT | Always |
| Connect to live systems | Human reviewer | None | Not authorized by this document |
| Deploy anything | Human reviewer | None | Not authorized by this document |
| Handle secrets | Human reviewer | None | Not authorized by this document |

## Command Formats

### Safe Task Brief

Use this format when handing work from Jarvis or ChatGPT to Codex, Claude Code, or OpenClaw:

```text
Task:
Repository scope:
Files likely affected:
Documentation-only confirmation:
Safety limits:
Expected output:
Review needed:
```

### Codex Edit Request

Use this format for repository documentation edits:

```text
Task: Create or update documentation only.
Files likely affected:
Required context files:
Do not add secrets.
Do not deploy.
Do not modify production systems.
Commit changes on a branch and prepare a pull request summary.
```

### Claude Code Review Request

Use this format for reviewing repository changes:

```text
Review the changed documentation files.
Confirm the change is documentation only.
Check entity names for consistency.
Check that ministry, foundation, church, business, and operations roles stay separated.
Check that no secrets, deployments, live integrations, or production changes were added.
Return comments or documentation-only suggestions.
```

### OpenClaw Routing Note

Use this format for future orchestration tracking:

```text
Command received:
Assigned tool:
Reason for routing:
Safety boundary checked:
Files or docs involved:
Human review status:
Next safe step:
```

## Escalation Rules

Escalate to a human reviewer before continuing when a command includes or implies:

- Legal structure decisions.
- Tax or compliance statements.
- Donor-facing commitments.
- Financial commitments.
- Banking, payment, fundraising platform, or donor data access.
- Live website, email, hosting, or production system access.
- Credentials, API keys, passwords, tokens, or service account files.
- Deployment, infrastructure changes, or automation that writes to live systems.
- New official operating procedures that have not been approved.

## Stop Conditions

Stop the command and do not route it to another AI tool if it requires:

- Secret handling.
- Production access.
- Deployment.
- Live system mutation.
- Donor private data.
- Payment data.
- Banking data.
- Legal, tax, compliance, or financial approval from an AI tool.

The next step in these cases is human review, not AI execution.

## Entity Naming Rules

Use these names consistently:

- Rays of Resilience International Ministries.
- Rays of Resilience Foundation.
- Rays of Resilience International Ministries Limited.

Do not merge or combine the roles of these entities. Keep the parent ministry structure, foundation support structure, and Uganda operating entity clearly separated.

## Repository Entry Points

Before routing repository work, read these files:

- `AGENTS.md`
- `docs/overview/README.md`
- `docs/overview/ai-context.md`
- `docs/overview/ai-entry.md`
- `docs/overview/operations-manual.md`
- `docs/overview/ai-tooling-roadmap.md`

## Current Status

Status: documentation-only command routing plan.

This document does not authorize production access, secret handling, deployment, live integrations, or automated operational control.
