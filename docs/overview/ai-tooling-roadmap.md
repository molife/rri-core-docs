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
