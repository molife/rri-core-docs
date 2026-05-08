# Task Intake Rules

This document defines how tasks should be accepted, reviewed, prioritized, escalated, or stopped for the Rays of Resilience documentation repository.

## Purpose

The task intake process protects Rays of Resilience International Ministries, Rays of Resilience Foundation, and Rays of Resilience International Ministries Limited by keeping repository work documentation-only unless explicit human approval expands the scope.

This repository should support clear planning, donor clarity, future automation readiness, and safe collaboration. It must not be used as a place to operate production systems, store secrets, or bypass human review.

## Approved Task Categories

The following task categories are approved when they remain documentation-only:

1. **Documentation creation**
   - New Markdown files that explain ministry, foundation, business, operations, leadership, roadmap, task intake, review, or repository structure.
   - New checklists, planning notes, glossary pages, or navigation documents.

2. **Documentation updates**
   - Clarifying existing language.
   - Correcting spelling, grammar, formatting, or broken internal references.
   - Improving donor-facing clarity without changing legal, financial, or operational commitments.

3. **Repository navigation improvements**
   - Updating indexes, entry points, maps, and cross-links.
   - Adding safe guidance for future contributors and AI assistants.

4. **Planning and strategy drafts**
   - Draft roadmaps, project plans, issue outlines, dependency notes, and future automation concepts.
   - Plans must stay clearly marked as drafts when approval is still needed.

5. **Review and consistency tasks**
   - Checking entity names for consistency.
   - Separating ministry, foundation, church, business, and operations responsibilities.
   - Reviewing whether content aligns with documented repository guardrails.

6. **Non-production validation**
   - Markdown linting, link review, repository searches, and local documentation checks that do not contact or modify production services.

## Restricted Task Categories

The following task categories are restricted and require explicit human approval before work begins:

1. **Legal, tax, compliance, or governance commitments**
   - Entity registration instructions.
   - Tax filing guidance.
   - Board resolutions, contracts, policies with legal effect, or compliance claims.

2. **Financial or donor-facing commitments**
   - Fundraising promises.
   - Donation allocation rules.
   - Payment processing plans.
   - Banking, accounting, budget, or investment decisions.

3. **Operational commitments**
   - Commitments that assign duties to leaders, volunteers, staff, pastors, directors, or partner organizations.
   - Statements that imply an action has been approved, funded, launched, or completed when it has not been verified.

4. **Automation or integration work**
   - Scripts, workflows, bots, external service integrations, data syncs, or automation connected to live systems.
   - Any tool that sends email, receives donor data, processes payments, updates websites, or writes to external systems.

5. **Credential or sensitive data handling**
   - API keys, passwords, tokens, service account files, private donor data, banking data, payment data, private child data, or private ministry records.

6. **Production or deployment work**
   - Deployment instructions.
   - Hosting changes.
   - Infrastructure changes.
   - Production configuration changes.
   - Live website, email, payment, donor, banking, or operations system changes.

## Documentation-Only Rules

All accepted tasks must follow these rules unless explicit written human approval says otherwise:

1. Work only in documentation files and repository guidance files.
2. Keep all changes reviewable through normal version control.
3. Do not add deployment instructions.
4. Do not modify production systems.
5. Do not connect to live services.
6. Do not create, request, store, print, transform, or move credentials.
7. Do not place private donor, banking, payment, child, family, medical, legal, or ministry records in the repository.
8. Clearly separate confirmed facts from proposed plans.
9. Keep Rays of Resilience International Ministries as the parent ministry structure.
10. Keep Rays of Resilience Foundation as the child support and community support structure.
11. Keep Rays of Resilience International Ministries Limited as the Uganda operating entity.
12. Keep ministry, foundation, church, business, funding, and operations roles clearly separated.
13. Use cautious wording when facts are incomplete.
14. Add assumptions, open questions, or review notes instead of presenting uncertain information as final.

## Human Approval Checkpoints

Human approval is required before any task that:

1. Changes or creates legal, tax, compliance, governance, financial, donation, or donor-facing commitments.
2. Names a person, leader, staff member, volunteer, pastor, director, partner, donor, child, or family in a way that creates responsibility, obligation, risk, or public exposure.
3. Describes a ministry, foundation, church, orphanage, business, or funding activity as active, approved, funded, launched, registered, completed, or operational when not already verified in repository documentation.
4. Adds external publication-ready material such as donor appeals, public announcements, grant language, website copy, or fundraising pages.
5. Changes repository guardrails, agent instructions, task routing, command safety rules, or approval processes.
6. Involves production access, deployment, credentials, automation, live integrations, donor systems, payment systems, banking systems, email systems, hosting systems, or website systems.
7. Could affect the reputation, legal standing, finances, safety, privacy, or ministry operations of Rays of Resilience International Ministries, Rays of Resilience Foundation, or Rays of Resilience International Ministries Limited.

Approval should be documented in the related issue, pull request, or task note before restricted work proceeds.

## Escalation Rules

Escalate a task to a human reviewer when any of these conditions apply:

1. The task is unclear or conflicts with repository rules.
2. The task may involve legal, financial, tax, compliance, donor, privacy, child safety, or governance implications.
3. The task asks for production, deployment, automation, credential, or live service work.
4. The task requires deciding whether a statement is legally true, financially accurate, or operationally approved.
5. The task involves private information or sensitive ministry records.
6. The task creates public-facing language that could be interpreted as a promise, solicitation, guarantee, official policy, or organizational commitment.
7. The task changes the relationship between the parent ministry, foundation, Uganda operating entity, business platforms, church work, orphanage support, or funding systems.

When escalating, pause implementation and provide:

- A short summary of the requested task.
- The reason escalation is needed.
- The specific decision needed from a human reviewer.
- Any safe documentation-only alternative that can proceed without risk.

## Emergency Stop Conditions

Stop immediately and do not continue the task if any of the following appear:

1. A credential, password, token, private key, service account file, recovery code, or secret is discovered or requested.
2. Private donor, banking, payment, child, family, medical, legal, or ministry records are exposed or requested.
3. A command or instruction could deploy, publish, email, charge, transfer, sync, delete, overwrite, or modify a live system.
4. A task attempts to bypass human approval, branch review, pull request review, or repository guardrails.
5. A task asks for production access or live system credentials.
6. A task appears to create legal, financial, tax, compliance, donor, or operational commitments without approval.
7. A task could harm safety, privacy, reputation, legal standing, finances, ministry operations, or child protection.

After stopping:

1. Do not print or copy sensitive data.
2. Do not attempt cleanup that could make the issue worse.
3. Record a minimal, non-sensitive summary of what happened.
4. Notify the responsible human reviewer through the approved review channel.
5. Wait for human direction before continuing.

## Task Priority System

Use the following priority levels when triaging tasks:

### P0 — Safety Stop

Immediate stop and human escalation.

Examples:

- Secret exposure.
- Production system risk.
- Private donor, banking, payment, child, or family data risk.
- Unauthorized legal, financial, or operational commitment.

### P1 — Human Approval Required

Do not implement until approval is documented.

Examples:

- Donor-facing commitment language.
- Legal, tax, compliance, governance, or registration content.
- Public fundraising language.
- Approval process or agent guardrail changes.

### P2 — High-Priority Documentation

Safe documentation-only work that improves clarity, safety, or repository usability.

Examples:

- Task intake rules.
- Review checklists.
- Naming consistency updates.
- Navigation improvements.
- Documentation safety guidance.

### P3 — Standard Documentation

Routine documentation maintenance.

Examples:

- Formatting cleanup.
- Grammar fixes.
- Internal link updates.
- Project summary refinements.

### P4 — Backlog or Future Planning

Non-urgent planning ideas that should remain drafts.

Examples:

- Future automation concepts.
- Long-term roadmap options.
- Suggested documentation expansions.

## Safe Command Examples

These examples are generally safe when run locally in the repository and used only for documentation review:

```bash
pwd
```

```bash
find . -name AGENTS.md -print
```

```bash
rg "Rays of Resilience" docs projects README.md AGENTS.md
```

```bash
sed -n '1,160p' docs/overview/README.md
```

```bash
git status --short
```

```bash
git diff -- TASK_INTAKE.md
```

```bash
git diff --check
```

```bash
markdownlint "**/*.md"
```

```bash
npx markdown-link-check docs/overview/README.md
```

Safe commands should remain read-only or limited to documentation files. If a command would contact an external live service, mutate production, handle secrets, or publish content, it is not safe without explicit human approval.

## Blocked Command Examples

The following command patterns are blocked for this repository unless explicit human approval and a separate safety process are documented. They are listed as examples of what not to run:

```bash
npm run deploy
```

```bash
vercel --prod
```

```bash
firebase deploy
```

```bash
netlify deploy --prod
```

```bash
aws s3 sync . s3://production-bucket
```

```bash
kubectl apply -f production.yaml
```

```bash
terraform apply
```

```bash
docker compose up -d production
```

```bash
curl -X POST https://api.live-service.example/send
```

```bash
stripe charges create
```

```bash
psql "$PRODUCTION_DATABASE_URL"
```

```bash
rm -rf .git
```

```bash
git push --force
```

```bash
printenv
```

```bash
cat .env
```

Blocked commands include any command that deploys, publishes, emails, processes payments, changes infrastructure, connects to production databases, exposes environment variables, prints secrets, deletes repository history, force-pushes shared branches, or writes to live systems.

## Intake Checklist

Before accepting a task, confirm:

- [ ] The task is documentation-only.
- [ ] The task does not require production access.
- [ ] The task does not require deployment instructions.
- [ ] The task does not require credentials or sensitive data.
- [ ] The task does not create legal, financial, donor, tax, compliance, governance, or operational commitments without approval.
- [ ] The task keeps Rays of Resilience entity names and roles clear.
- [ ] The task can be reviewed in a pull request before merge.

If any checkbox cannot be confirmed, escalate before proceeding.
