# OctoAcme Project Management Docs

This README introduces OctoAcme's project management methodology and links to all core process documents in this repository. Use this file as your entry point to understand how OctoAcme manages projects from initiation through retrospective, and to quickly locate the right artifact or process guide.

## Summary of Project Management Processes

OctoAcme's project management approach follows a lightweight, end-to-end lifecycle designed for cross-functional delivery: **Initiation → Planning → Execution → Release → Close/Retrospective**. Work typically begins with a **Project One-pager/Charter** that clarifies the problem, SMART objectives, success metrics, stakeholders, rough timeline, risks, and resourcing. A decision gate is used to move from initiation into planning once success metrics are clear, stakeholder alignment is confirmed, and team availability is validated.

Once approved, planning focuses on converting the initiative into an actionable delivery plan. The team holds a kickoff, builds a **prioritized backlog with acceptance criteria**, estimates work (e.g., T-shirt sizing or story points), defines a clear **Definition of Done**, and maps milestones and releases. Risks and dependencies are captured in a **Risk Register** (impact/likelihood/owner/mitigation/status) and are treated as first-class planning artifacts, with cross-team dependencies explicitly tracked and escalated as needed.

Execution is managed through a visible workflow on a project board (commonly: **Backlog → Ready → In Progress → In Review → QA → Done**) and a pull-request process that emphasizes small, reviewable changes, clear linkage to issues and acceptance criteria, CI validation, and at least one approval before merge. Core personas support clear ownership: **Project Managers** coordinate delivery mechanics, schedule, risk, and communications; **Product Managers** define outcomes and prioritize; **Developers** implement, test, and collaborate on design/reviews; **QA/Testing** validates quality and acceptance; and **Stakeholders** provide input and approvals.

Communication and quality practices are embedded throughout delivery. OctoAcme uses a regular team rhythm (standups, weekly delivery syncs, and sprint/milestone demos) plus structured stakeholder updates using consistent status templates. Quality assurance includes unit/integration testing, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Releases are standardized with pre-release requirements (all acceptance criteria met, CI/security green, release notes, rollback plan, smoke tests) and deployment checklists. The team closes each cycle through retrospectives that produce a small number of owned, time-bound improvement actions tracked back in the backlog.

## Key Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

Refer to each document for detailed guidance, templates, and checklists. To update or add a process document, open a pull request against `main` and link it to the relevant issue.
