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

OctoAcme follows a lightweight, iterative project lifecycle that begins with a focused initiation step and moves through planning, execution, release, and continuous improvement. Initiatives start with a Project One-pager that captures the problem, goals, and measurable success metrics, and a decision gate confirms readiness to plan. Planning breaks approved work into prioritized, estimable backlog items with clear acceptance criteria and a Definition of Done.

Day-to-day delivery is managed through an explicit team rhythm and visible workflows: short daily standups for blockers, weekly delivery syncs for progress and cross-team issues, and demos at the end of sprints or milestones. Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and pull requests should be small, link to issues and acceptance criteria, and pass CI and lint checks before review.

Roles and personas are defined to ensure clarity of ownership: Project Managers coordinate delivery, schedules, risk registers, and stakeholder communication; Product Managers define outcomes, prioritize the backlog, and measure success; Developers implement and test changes and participate in design reviews; QA validates acceptance criteria and coordinates manual and automated verification. Escalation paths move issues from team triage to PM → Product Lead → Sponsor when needed.

Quality practices include unit and integration tests for new logic, end-to-end or smoke tests for critical flows, automated security scanning in CI, and manual QA for feature acceptance when required. Pre-release gates require passing CI/security scans, drafted release notes, a rollback plan, and staging verification. After releases or incidents, the team runs blameless retrospectives and converts action items into tracked backlog work to measure and close the continuous improvement loop.
