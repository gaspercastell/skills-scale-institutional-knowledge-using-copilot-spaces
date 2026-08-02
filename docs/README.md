# OctoAcme Project Management Docs

This README indexes OctoAcme's project management process documents and provides a brief overview of the key workflows, roles, communication strategies, and quality practices used across projects.

Links
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospectives & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

Overview

OctoAcme follows a lightweight, iterative project lifecycle that begins with a focused initiation step and moves through planning, execution, release, and continuous improvement. Initiatives start with a one‑pager capturing the problem, goals, and measurable success metrics, and stakeholders are aligned before the team commits to planning. Planning produces a prioritized backlog, estimates, a Definition of Done, and a release/milestone plan; risks and cross‑team dependencies are recorded in a simple risk register with owners and mitigations.

Day‑to‑day delivery uses a consistent team rhythm and explicit workflows to keep work visible and progressing. The team runs short daily standups for blockers, weekly delivery syncs for progress and risk review, and demos at the end of iterations or milestones. Work is managed on a project board with clear column states (Backlog → Ready → In Progress → In Review → QA → Done) and pull requests follow defined rules (small PRs, link to issues and acceptance criteria, CI and lint checks before review, and at least one approval before merging).

Clear roles and communication reduce friction and speed decisions. Project Managers coordinate schedules, risks, and stakeholder communication while Product Managers define outcomes and prioritize the backlog. Developers implement and test, QA validates acceptance criteria and feature quality, and stakeholders act as decision owners when approvals are needed. Escalation paths are documented so issues move from team triage to PM and product leads and up to sponsors for business‑impacting concerns.

Quality is enforced through testing, CI checks, and pre‑release controls. Developers write unit and integration tests, critical flows have end‑to‑end or smoke tests, and security scanning runs in CI. Pre‑release gates include passing CI/security scans, drafted release notes, a rollback plan, and staging verification. After releases or incidents the team conducts blameless retrospectives, turns action items into tracked work, and measures impact to close the improvement loop.
