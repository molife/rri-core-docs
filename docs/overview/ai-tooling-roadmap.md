# AI Tooling Roadmap

## Purpose

This roadmap describes a safe documentation-first path for connecting ChatGPT, Claude Code, and Codex to the Rays of Resilience documentation repository.

The goal is to improve planning, drafting, review, and documentation quality without changing production systems, adding secrets, or deploying anything.

## Current Repository Role

This repository is the source of truth for Rays of Resilience structure, projects, operations, leadership, funding, business platforms, church development, orphanage support, foundation work, priorities, and roadmap.

Primary entry points:

- `AGENTS.md`
- `docs/overview/README.md`
- `docs/overview/ai-context.md`
- `docs/overview/ai-entry.md`
- `docs/overview/operations-manual.md`

## Safety Rules

All AI tools must follow these rules:

1. Documentation only unless Roman gives written approval for a wider scope.
2. Do not change production systems.
3. Do not add, request, store, or expose secrets.
4. Do not deploy anything.
5. Do not connect tools directly to payment, donor, banking, website, email sending, hosting, or live ministry systems.
6. Do not edit legal, financial, tax, compliance, or donor-facing commitments without human review.
7. Use branches and pull requests for changes when possible.
8. Keep all entity names consistent.
9. Keep ministry, foundation, church, and business roles separated.
10. Record assumptions inside documentation when facts are incomplete.

## Tool Roles

### ChatGPT

Best use:

- Planning documentation structure
- Drafting policies, roadmaps, summaries, and donor clarity documents
- Reviewing wording for consistency
- Creating issue checklists and documentation tasks
- Explaining repository structure for collaborators

Allowed scope:

- Read documentation
- Propose documentation updates
- Create documentation drafts
- Review pull requests for clarity and consistency

Not allowed without explicit approval:

- Production changes
- Secret handling
- Deployment work
- Live automation connected to external systems

### Claude Code

Best use:

- Local repository review
- Markdown cleanup
- Link checks
- File organization
- Refactoring documentation structure
- Preparing documentation-only pull requests

Allowed scope:

- Documentation files
- Markdown formatting
- Navigation updates
- Non-production repository hygiene

Not allowed without explicit approval:

- Scripts that call live services
- Credential handling
- Deployment configuration changes
- Automated writes to production systems

## Claude Code Connection

Claude Code may be connected to a local clone of this repository as a documentation assistant only. Its connection should support careful reading, review, and planning while preserving the repository's documentation-first safety boundary.

### Safe Claude Code Responsibilities

Claude Code should:

- Read repository documentation before suggesting changes.
- Start with the primary entry points in `AGENTS.md`, `docs/overview/README.md`, `docs/overview/ai-context.md`, `docs/overview/ai-entry.md`, `docs/overview/operations-manual.md`, and this roadmap.
- Review Codex changes for clarity, consistency, navigation quality, and alignment with Rays of Resilience structure.
- Suggest architecture improvements for documentation organization, future automation planning, repository navigation, review workflows, and safe tool boundaries.
- Keep recommendations separated from implementation when human approval is still needed.
- Update documentation only unless Roman gives explicit written approval for a broader scope.

### Claude Code Safety Boundaries

Claude Code must never:

- Touch, request, store, print, or move secrets, including API keys, passwords, tokens, donor private data, payment data, banking data, hosting credentials, email credentials, or service account files.
- Deploy anything.
- Change production systems.
- Connect this repository to live payment, donor, banking, website, email sending, hosting, or ministry operations systems.
- Modify deployment configuration, infrastructure configuration, or automation that could write to live systems without explicit written approval and human review.
- Convert planning notes into operational commitments without human review.

### Claude Code Review Workflow

When reviewing Codex changes, Claude Code should use this sequence:

1. Read the changed files and nearby context.
2. Confirm the change is documentation only.
3. Check entity names for consistency.
4. Check that ministry, foundation, church, and business roles remain separated.
5. Check that no secrets, live integrations, deployment steps, or production changes were added.
6. Suggest wording, structure, link, or architecture improvements as comments or documentation-only edits.
7. Escalate to human review when a change affects legal, financial, donor-facing, compliance, tax, production, or operational commitments.

### Codex

Best use:

- Structured documentation edits
- Repository-wide search and update tasks
- Drafting safe implementation notes
- Creating issue-based work plans
- Preparing pull requests for review

Allowed scope:

- Documentation-only edits
- Branch-based changes
- Pull request summaries
- Test plans limited to documentation validation

Not allowed without explicit approval:

- Production code changes
- Secret creation or storage
- Deployment execution
- Infrastructure changes

## Connection Model

Use this order:

1. Read-only review
2. Documentation draft
3. Branch-based documentation update
4. Human review
5. Merge after approval

Avoid this order:

1. Direct production access
2. Secret sharing
3. Automated deployment
4. Live system mutation

## Recommended Repository Permissions

### Minimum Safe Setup

- ChatGPT: repository read access plus documentation PR creation only
- Claude Code: local clone with no production credentials
- Codex: repository read access plus branch and PR permissions for documentation only

### Branch Protection

Recommended controls:

- Require pull requests before merge
- Require review before merge
- Protect `main`
- Disable direct commits to `main` where possible
- Require conversation resolution before merge

## Documentation Workflow

Use this workflow for all AI-assisted documentation work:

1. Start from `docs/overview/ai-entry.md`.
2. Read `docs/overview/ai-context.md` for organization context.
3. Read `AGENTS.md` for repository rules.
4. Identify the documentation file that should change.
5. Draft the change in a branch.
6. Summarize what changed and what did not change.
7. Confirm that no secrets, deployments, production edits, or live integrations were added.
8. Request human review.

## First Safe Milestones

### Phase 1: Documentation Guardrails

- Add this roadmap.
- Update AI entry points to reference this roadmap.
- Add clear AI safety rules to `AGENTS.md`.
- Confirm all links in overview files are accurate.

### Phase 2: Tool Onboarding Notes

- Add a short setup note for ChatGPT repository use.
- Add a short setup note for Claude Code local documentation review.
- Add a short setup note for Codex documentation-only pull requests.

### Phase 3: Review Checklist

- Add a documentation review checklist.
- Add a donor-facing wording checklist.
- Add a naming consistency checklist.

### Phase 4: Optional Automation Planning

Plan only. Do not connect live systems.

Possible future documentation-only planning areas:

- Issue templates
- Pull request templates
- Documentation linting
- Broken link checks
- Repository navigation cleanup

### Phase 5: Future Orchestration Layer

OpenClaw and Jarvis may be evaluated later as an orchestration layer for coordinating AI-assisted documentation workflows. This phase is future planning only and does not authorize implementation, deployment, production access, or secret handling.

Possible future orchestration responsibilities:

- Route documentation tasks between ChatGPT, Claude Code, Codex, and human reviewers.
- Track documentation review status and required approvals.
- Maintain a safe task queue for documentation-only updates.
- Coordinate architecture suggestions without applying production changes.
- Produce audit-friendly summaries of what each AI tool reviewed or changed.

OpenClaw and Jarvis must remain outside live ministry, donor, payment, banking, email, hosting, and website systems unless Roman gives explicit written approval, human review is complete, and separate safety documentation is created first.

## Documentation-Only PR Checklist

Before any AI-assisted pull request is merged, confirm:

- [ ] The change is documentation only.
- [ ] No secrets were added.
- [ ] No production system was changed.
- [ ] No deployment was performed.
- [ ] No live external integration was added.
- [ ] Entity names remain consistent.
- [ ] Ministry, foundation, church, and business roles remain separated.
- [ ] Human review is complete.

## Stop Conditions

Stop work and request human review if any task requires:

- API keys
- Passwords
- Tokens
- Payment data
- Donor private data
- Live website access
- Hosting access
- Email sending access
- Banking access
- Legal, tax, or compliance commitments
- Deployment permissions

## Current Status

Status: planning and documentation only.

No production systems are connected by this roadmap.
No secrets are required by this roadmap.
No deployments are authorized by this roadmap.
