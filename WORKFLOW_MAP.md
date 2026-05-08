# Rays of Resilience AI Workflow Map

## Purpose

This document maps the safe, documentation-only workflow for moving work through:

ChatGPT → Codex → Claude Code → OpenClaw → Jarvis → approved execution layer.

The workflow is designed to support planning, drafting, review, testing, approval, blocking, emergency stop handling, and future production planning while protecting Rays of Resilience International Ministries, Rays of Resilience Foundation, and Rays of Resilience International Ministries Limited.

## Scope and Safety Boundary

This repository remains documentation-only unless Roman gives explicit written approval for a wider scope.

This workflow does not authorize:

- Secrets, passwords, API keys, tokens, or credentials in repository files.
- Deployment work.
- Production changes.
- Direct writes to live ministry, donor, payment, banking, website, hosting, email, or operating systems.
- Legal, financial, tax, compliance, or donor-facing commitments without human review.

All tools must keep the roles of Rays of Resilience International Ministries, Rays of Resilience Foundation, Rays of Resilience International Ministries Limited, ministry projects, church work, orphanage support, foundation programs, and business platforms clearly separated.

## Tool Chain Overview

```text
ChatGPT
  ↓ planning and drafting
Codex
  ↓ repository documentation edits and pull request preparation
Claude Code
  ↓ local review, cleanup, consistency, and documentation architecture checks
OpenClaw
  ↓ future orchestration planning and safe task routing
Jarvis
  ↓ future command coordination with approval gates
approved execution layer
  ↓ human-approved action only
```

## Tool Responsibilities

### ChatGPT

Primary role: planning and documentation drafting.

ChatGPT may:

- Clarify goals and intended audience.
- Draft workflow plans, documentation outlines, checklists, and summaries.
- Review wording for donor clarity and organizational consistency.
- Convert human direction into documentation tasks.

ChatGPT must not:

- Request or store secrets.
- Approve production changes.
- Perform deployments.
- Connect to live external systems.

### Codex

Primary role: repository-based documentation editing.

Codex may:

- Read approved repository context.
- Create and update Markdown documentation.
- Run documentation-safe checks.
- Commit documentation-only changes on the current branch.
- Prepare pull request summaries for review.

Codex must not:

- Add credentials or live integration details.
- Modify production systems.
- Deploy anything.
- Expand scope beyond documentation without explicit written approval.

### Claude Code

Primary role: local documentation review and refinement.

Claude Code may:

- Review Codex changes for clarity, consistency, and structure.
- Check Markdown navigation and links.
- Suggest safer wording and better documentation organization.
- Confirm that entity names and roles stay consistent.

Claude Code must not:

- Convert plans into live operational commitments.
- Touch secrets or production settings.
- Deploy or connect live systems.
- Approve high-risk work without human review.

### OpenClaw

Primary role: future orchestration planning only.

OpenClaw may be planned as a coordinator that:

- Routes documentation tasks between tools.
- Tracks review status.
- Maintains task queues for documentation-only work.
- Records blocked items and approval requirements.

OpenClaw must remain disconnected from production systems unless separate approval, safety documentation, and human review are completed first.

### Jarvis

Primary role: future command coordination only.

Jarvis may be planned as a controlled coordination layer that:

- Receives approved tasks from OpenClaw.
- Checks whether approvals are present.
- Prepares execution requests for a human-approved layer.
- Logs what was requested, approved, blocked, or stopped.

Jarvis must not execute production actions, request secrets, or bypass approval gates.

### Approved Execution Layer

Primary role: future human-approved action layer.

The approved execution layer may only act when:

- The task has written human approval.
- The scope is documented.
- Required reviewers have approved the action.
- Safety checks are complete.
- Rollback or stop instructions are documented when relevant.

For this repository today, the approved execution layer is documentation-only.

## Planning Workflow

Use this workflow before any documentation task starts:

1. Human defines the goal, audience, and boundaries.
2. ChatGPT turns the goal into a draft plan or checklist.
3. Codex reads repository context and identifies affected documentation files.
4. Codex confirms the task is documentation-only.
5. Claude Code reviews the plan for clarity, entity consistency, and safe scope.
6. OpenClaw may be used in the future to record task status and route work.
7. Jarvis may be used in the future to verify approval gates before any execution request.
8. Human confirms whether work may proceed.

Planning output should include:

- Purpose.
- Files expected to change.
- Entity names involved.
- Assumptions.
- Safety limits.
- Review requirements.

## Documentation Workflow

Use this workflow for normal documentation updates:

1. ChatGPT drafts or refines the content plan.
2. Codex updates Markdown files in a branch.
3. Codex keeps changes documentation-only.
4. Codex checks that no secrets, deployments, live integrations, or production changes were added.
5. Claude Code reviews structure, wording, navigation, and consistency.
6. Human reviews the pull request.
7. Approved documentation is merged only after review.

Documentation updates should preserve:

- Rays of Resilience International Ministries as the parent ministry structure.
- Rays of Resilience Foundation as the child support and community support structure.
- Rays of Resilience International Ministries Limited as the Uganda operating entity.
- Clear separation between ministry, foundation, church, orphanage, and business platform roles.

## Review Workflow

Every AI-assisted change should be reviewed in this order:

1. Codex self-checks the changed files.
2. Claude Code checks documentation quality and consistency.
3. Human reviewer checks organizational accuracy and approval readiness.
4. Human reviewer confirms no restricted content was introduced.
5. Pull request comments are resolved before merge.

Review checklist:

- [ ] Documentation-only change.
- [ ] No secrets or credentials.
- [ ] No deployment instructions that perform live deployment.
- [ ] No production system changes.
- [ ] No live donor, payment, banking, website, hosting, or email integrations.
- [ ] Entity names are consistent.
- [ ] Legal, financial, tax, compliance, and donor-facing commitments have human review.
- [ ] Ministry, foundation, church, orphanage, and business roles remain separated.

## Testing Workflow

Testing for this repository means documentation validation only.

Safe checks may include:

- Git status review.
- Markdown formatting review.
- Link checks against repository files.
- Search for prohibited secret-like terms when appropriate.
- Review of changed files and nearby context.

Testing must not include:

- Deployment tests.
- Live API calls.
- Payment processing tests.
- Email sending tests.
- Donor database tests.
- Website production mutation.

Testing flow:

1. Codex runs documentation-safe checks.
2. Codex records exact commands used in the pull request or final summary.
3. Claude Code may repeat or expand documentation checks.
4. Human reviewer decides whether checks are sufficient.
5. Any failed safety check moves the task to the blocked workflow.

## Approval Workflow

Approval is required before any change is merged or any future execution step is allowed.

Approval levels:

### Documentation Approval

Required for:

- Markdown documentation updates.
- Navigation changes.
- Roadmaps, workflow maps, checklists, and planning documents.

Approver:

- Roman or a designated human reviewer.

### Sensitive Documentation Approval

Required for:

- Donor-facing language.
- Legal, financial, tax, or compliance references.
- Public commitments.
- Governance or leadership responsibility changes.

Approver:

- Roman and any required qualified advisor or designated reviewer.

### Future Execution Approval

Required for any future non-documentation task.

Approver:

- Roman, plus any required operational, legal, financial, technical, or ministry leadership reviewer.

Future execution approval must include:

- Written scope.
- Named approver.
- Date of approval.
- Risk review.
- Stop condition.
- Rollback or reversal plan when relevant.

## Blocked Workflow

A task is blocked when it requires information, permission, or access that is not available or not safe.

Block immediately if the task requires:

- API keys, passwords, tokens, or credentials.
- Donor private data.
- Payment, banking, tax, or compliance data.
- Live website, hosting, email, payment, banking, or ministry system access.
- Deployment permissions.
- Legal, financial, or donor-facing commitments without review.
- Entity name changes that could confuse legal or ministry structure.

Blocked flow:

1. Stop active changes.
2. Record what is blocked.
3. Record why it is blocked.
4. Identify the human approval or missing information required.
5. Do not create workarounds that bypass the block.
6. Resume only after the blocker is resolved in writing.

Blocked task note format:

```text
Blocked item:
Reason:
Risk:
Needed approval or information:
Allowed next step:
```

## Emergency Stop Workflow

The emergency stop workflow is used when a safety boundary may have been crossed.

Trigger emergency stop if:

- A secret or credential is discovered in repository content.
- A tool attempts to deploy or modify production systems.
- A task starts using live donor, payment, banking, website, hosting, email, or ministry operations access.
- A change creates legal, financial, tax, compliance, or donor-facing risk without approval.
- A tool continues after being blocked.

Emergency stop flow:

1. Stop all tool activity immediately.
2. Do not print, copy, or move any discovered secret.
3. Notify the human reviewer.
4. Preserve enough non-sensitive context to explain what happened.
5. Remove or quarantine unsafe documentation content only with human direction.
6. Rotate or revoke exposed credentials outside this repository if needed.
7. Document the incident summary without including secrets.
8. Resume only after Roman or a designated human reviewer approves restart.

Emergency stop note format:

```text
Emergency stop triggered:
Date:
Trigger:
Affected files or systems:
Sensitive content exposed? yes/no/unknown
Immediate action taken:
Human reviewer needed:
Restart allowed? yes/no
```

## Production Workflow for Future Use Only

This section is planning-only. It does not authorize production work now.

A future production workflow may be considered only after separate approval and safety documentation are created.

Future production prerequisites:

- Written approval from Roman.
- Clear production scope.
- Named human owner.
- Qualified technical reviewer.
- Security review.
- Secret handling plan outside the repository.
- Test environment separate from production.
- Backup or rollback plan.
- Emergency stop procedure.
- Post-action review.

Future production flow:

1. ChatGPT helps draft the production change plan in documentation.
2. Codex prepares documentation and checklists only.
3. Claude Code reviews the plan and identifies documentation risks.
4. OpenClaw tracks approvals and readiness only.
5. Jarvis checks that all approval gates are present only.
6. Human reviewer confirms production readiness.
7. Approved execution layer performs only the specifically approved action.
8. Human reviewer verifies the outcome.
9. Documentation is updated with a non-sensitive summary.

Production work remains prohibited until all prerequisites are completed outside this documentation-only workflow.

## Handoff Summary Format

Use this format when moving work from one tool or reviewer to another:

```text
Task:
Current owner:
Next owner:
Files changed or reviewed:
Summary:
Safety checks completed:
Open questions:
Blocked items:
Approval needed:
```

## Current Status

Current status: documentation-only workflow map.

No secrets are required.
No deployments are authorized.
No production changes are authorized.
No live systems are connected.
