# OctoAcme Project Management Processes

Welcome to the OctoAcme Project Management Documentation Hub. This folder contains our standardized approaches for running projects from initiation through delivery and retrospective.

## Our Approach

OctoAcme projects follow a structured lifecycle with clear phases, defined roles, and regular checkpoints. We prioritize customer value, iterative delivery, clear ownership, and data-informed decisions.

### Core Principles

- **Customer-first**: prioritize customer value and usability
- **Iterative delivery**: deliver small, testable increments
- **Clear ownership**: each project has a named PM and Product Lead
- **Data-informed decisions**: measure impact and iterate based on evidence
- **Psychological safety**: encourage feedback and learning

## The OctoAcme Project Management Framework

OctoAcme uses a structured, stage-gated process that starts with initiation and ends with release, retrospective, and continuous improvement. New work begins with a lightweight project initiation review: confirming the business need, defining stakeholders, success metrics, and a high-level timeline, then deciding whether to proceed into planning. Once approved, the team moves into planning by creating a prioritized backlog, estimating scope, defining the Definition of Done, identifying dependencies and risks, and agreeing on milestones and release timing. Execution follows a disciplined cadence with daily standups, weekly delivery syncs, sprint or milestone reviews, and explicit tracking through a project board with states such as Backlog, Ready, In Progress, In Review, QA, and Done. This keeps the work iterative and transparent while ensuring each phase produces reviewable, shippable outcomes.

The process is built around clear roles and responsibilities. Product managers define outcomes, success metrics, and backlog priorities; project managers coordinate schedules, communication, risks, and dependencies; developers build and test the solution; QA validates that the work meets acceptance criteria; and stakeholders provide alignment, feedback, and approvals. Communication is a core part of OctoAcme's operating model with a regular cadence of weekly PM/PdM syncs, twice-weekly delivery standups, monthly stakeholder updates, and ad hoc escalations when blockers arise. Quality assurance and release controls are built into the framework with unit tests, integration and end-to-end smoke tests, automated testing in CI, and defined deployment checklists with rollback planning. Retrospectives after sprints and incidents capture lessons learned and turn them into action items for continuous improvement.

## Process Documents

| Phase | Document | Purpose |
|-------|----------|---------|
| Initiation | [Project Initiation Guide](octoacme-project-initiation.md) | Define business need, stakeholders, and initial timeline |
| Planning | [Project Planning](octoacme-project-planning.md) | Break work into shippable increments and identify risks |
| Execution | [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day progress and team rhythm |
| Release | [Release & Deployment](octoacme-release-and-deployment.md) | Standardize release processes and reduce deployment risk |
| Closure | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive improvements |
| Cross-cutting | [Risk Management & Communication](octoacme-risks-and-communication.md) | Manage risks and stakeholder communication throughout |
| Reference | [Roles & Personas](octoacme-roles-and-personas.md) | Define core roles and responsibilities |
| Reference | [Project Management Overview](octoacme-project-management-overview.md) | High-level summary for quick reference |

## How to Use These Documents

- **New to OctoAcme projects?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to our approach, roles, and key artifacts.
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate the business need and get stakeholder alignment.
- **Ready to plan?** Use [Project Planning](octoacme-project-planning.md) to break work into manageable increments and identify dependencies.
- **In active delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for guidance on daily standups, PR workflows, quality gates, and progress tracking.
- **Managing risks and stakeholders?** [Risk Management & Communication](octoacme-risks-and-communication.md) provides templates and escalation paths.
- **Preparing for release?** [Release & Deployment](octoacme-release-and-deployment.md) covers pre-release requirements, deployment checklists, and rollback procedures.
- **Wrapping up a project?** [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guides you through capturing learnings and action items.

## Quick Reference Checklists

### Project Initiation Checklist
- [ ] One-pager completed and reviewed by Product Lead
- [ ] Sponsor / Stakeholder alignment (email or meeting)
- [ ] Decision: Approve to move into planning?
- [ ] Create repo or project board skeleton
- [ ] Add initial artifacts to repo (docs/ or .copilot/)

### Planning Checklist
- [ ] Project kickoff held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan / QA approach drafted

### Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

### Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed role descriptions.

## Communication Cadence

- **Daily**: Standups (15 min) — focus on progress, blockers, dependencies
- **Twice weekly**: Delivery team standups (or as agreed)
- **Weekly**: PM + PdM sync and delivery sync with stakeholder updates
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communications

## Questions or Feedback?

If you have suggestions for improving these processes or identify gaps in the documentation, please create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
