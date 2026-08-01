# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation. These documents describe how we start, plan, deliver, release, and continuously improve projects so contributors and stakeholders can quickly find and apply our standard practices.

OctoAcme follows a lightweight, stage-based lifecycle: Initiation (capture problem statements, stakeholders, and a Project One‑pager), Planning (backlog creation, estimates, Definition of Done, and release/milestone mapping), Execution (iterative delivery via a project board and small, reviewable PRs), Release (checklists, smoke tests, and rollback plans), and Close (retrospectives and tracked action items). Key artifacts such as the Project One‑pager, acceptance criteria on backlog items, the risk register, and release notes keep decisions and status transparent.

Workflows emphasize predictable, incremental delivery and clear handoffs: use a project board with Backlog → Ready → In Progress → In Review → QA → Done, keep pull requests small and linked to issues with acceptance criteria, and require passing CI and at least one approval before merging. Risk and dependency management are explicit — maintain a simple risk register that includes owner and mitigation, and escalate cross-team dependencies in weekly syncs.

Roles and communication are well-defined to reduce ambiguity. A named Project Manager coordinates delivery and communications while the Product Manager owns outcomes and success metrics. Developers, QA, and stakeholders collaborate through daily standups, weekly delivery syncs, sprint demos, and regular stakeholder updates. Quality assurance combines automated unit/integration tests, CI security scans, end-to-end smoke tests for critical flows, and manual QA when required. See the individual docs below for full details.

## Docs (links)
- [Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution and Tracking](docs/octoacme-execution-and-tracking.md)
- [Risks and Communication](docs/octoacme-risks-and-communication.md)
- [Release and Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

## How to contribute
- Propose edits as pull requests against the corresponding doc in docs/.
- For new process docs, create a file in docs/ and request this README be updated to include the link.
