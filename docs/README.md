# OctoAcme Project Management Docs

This directory contains OctoAcme's guidance for taking cross-functional projects from an initial idea through delivery and continuous improvement. The process emphasizes customer value, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

## Project lifecycle at a glance

1. **Initiate and authorize:** Validate the business need, define a measurable goal and success criteria, identify stakeholders, and record a high-level timeline, resources, risks, and dependencies in a project one-pager. Product Lead and stakeholder alignment informs the decision to proceed to planning.
2. **Plan:** Turn approved work into a prioritized backlog with acceptance criteria and estimates. Agree on scope, Definition of Done, responsibilities, milestones, release approach, test strategy, risks, and cross-team dependencies.
3. **Execute and track:** Deliver in small increments, using a project board to track work from Backlog through Ready, In Progress, In Review, QA, and Done. Keep progress, blockers, risks, and dependencies visible; use reviews and demos to gather feedback and adapt.
4. **Release and deploy:** Confirm acceptance criteria, passing CI and security scans, release notes, smoke tests, and a rollback or mitigation plan. Deploy, verify the result, and communicate the release to stakeholders and support.
5. **Close and improve:** After a sprint, release, milestone, or incident, capture what went well and what could improve. Assign a small number of actionable follow-ups with owners, due dates, and success criteria, then review them in the regular PM sync.

## Roles and communication

The **Project Manager (PM)** coordinates delivery, schedules, risks, resources, and communications. The **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success. **Developers** build, test, and review changes; **QA/Testing** validates quality and acceptance criteria; and **stakeholders** provide input and approvals. The team aligns through delivery-team standups, weekly PM–PdM and delivery syncs, sprint or milestone demos, and regular stakeholder updates. Status reporting should make progress, next steps, risks or blockers, and decisions needed clear. Escalations move from the team to the PM, then to the Product Lead and sponsor as appropriate; security incidents follow the security incident runbook and notify Security on-call.

## Quality practices

Quality is part of planning and delivery: define acceptance criteria and a Definition of Done; add unit tests for new logic and integration tests where applicable; run automated tests, linting, and security scanning in CI; and use manual QA or end-to-end smoke tests for critical flows as needed. Keep pull requests small where possible, link the related issue and acceptance criteria, and obtain at least one approval or follow the team's defined policy before merging. Before production release, verify readiness and prepare rollback or mitigation steps; after deployment, run post-deploy checks.

## Documents

- [Project Management Overview](octoacme-project-management-overview.md) — principles, roles, key artifacts, lifecycle, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validation, authorization, one-pager, and initiation decision gate.
- [Project Planning](octoacme-project-planning.md) — backlog, estimates, Definition of Done, milestones, risks, and dependencies.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, project board, PR workflow, quality checks, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk lifecycle, stakeholder updates, incident communication, and escalation paths.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release readiness, deployment checklist, rollback, incident response, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — retrospective structure and tracking improvement actions.
- [Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and typical communication for developers, product managers, and project managers.
