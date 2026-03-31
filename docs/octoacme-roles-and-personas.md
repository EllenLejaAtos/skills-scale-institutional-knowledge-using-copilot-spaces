# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master

### Role Summary
The Scrum Master serves as a servant-leader for the delivery team, facilitating Agile ceremonies, removing blockers, and coaching the team on continuous improvement practices.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove impediments that slow the team down
- Shield the team from unplanned interruptions and scope creep
- Coach the team on Agile principles and self-organization
- Track and report on sprint velocity and team health metrics

### Goals
- Maintain a healthy, predictable delivery cadence
- Continuously improve team processes and collaboration
- Foster a culture of transparency and learning

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment logs and retrospective action items
- Coaching conversations and team health check-ins

### Key Interactions
| Role | Interaction |
|---|---|
| Developers | Removes technical and organizational blockers; facilitates estimation and sprint planning |
| Product Managers | Aligns on sprint goals and backlog priorities; protects team capacity from ad-hoc requests |
| Project Managers | Shares velocity data and risk signals; coordinates on cross-team dependencies and milestones |

---

## UX Designer

### Role Summary
UX Designers ensure that user needs and usability are central to product decisions. They translate user research into designs and work with development teams to deliver high-quality user experiences.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and final design specifications
- Define and maintain design standards and component guidelines
- Participate in sprint reviews to validate design implementation
- Collaborate on acceptance criteria related to UX and accessibility

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce rework by aligning on designs before development begins
- Advocate for the end user throughout the project lifecycle

### Typical Communication
- Design reviews and critique sessions
- Annotated prototypes and design handoff notes
- Usability test reports and research summaries

### Key Interactions
| Role | Interaction |
|---|---|
| Developers | Provides design specs and assets; reviews implementation for fidelity and accessibility |
| Product Managers | Collaborates on user requirements, personas, and success metrics |
| Project Managers | Flags design dependencies and timeline needs for research or review cycles |

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the pipelines, infrastructure, and tooling that enable reliable, repeatable software delivery. They bridge development and operations to reduce toil and improve system stability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Manage infrastructure as code and environment consistency
- Monitor system health, alerts, and on-call responses
- Enforce security, compliance, and access controls in pipelines
- Support incident response, root cause analysis, and postmortems

### Goals
- Reduce deployment lead time and increase deployment frequency
- Minimize manual steps and environment drift
- Maintain high availability and rapid recovery capabilities

### Typical Communication
- Pipeline and infrastructure runbooks
- Incident reports and postmortem documents
- Release readiness confirmations and deployment plans

### Key Interactions
| Role | Interaction |
|---|---|
| Developers | Supports local environment setup, CI/CD onboarding, and build troubleshooting |
| Product Managers | Communicates infrastructure constraints that affect feature delivery timelines |
| Project Managers | Provides deployment readiness status and coordinates release windows |

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions by clarifying requirements, documenting processes, and ensuring that delivered features meet stakeholder expectations.

### Responsibilities
- Elicit, document, and validate requirements with stakeholders
- Translate business needs into clear, actionable user stories and acceptance criteria
- Analyze current-state processes and identify improvement opportunities
- Maintain traceability between requirements, features, and test cases
- Support user acceptance testing (UAT) and sign-off

### Goals
- Eliminate ambiguity in requirements before development begins
- Ensure delivered solutions meet business and user needs
- Reduce rework caused by misunderstood or incomplete requirements

### Typical Communication
- Requirements documents, user stories, and process diagrams
- Stakeholder interviews and workshop summaries
- UAT feedback and sign-off reports

### Key Interactions
| Role | Interaction |
|---|---|
| Developers | Clarifies requirements and acceptance criteria during implementation; reviews outputs against specs |
| Product Managers | Partners on backlog refinement and ensures business context is captured in stories |
| Project Managers | Flags scope changes and requirement dependencies that affect the project plan |

---

## Release Manager

### Role Summary
Release Managers coordinate release planning and execution across teams, ensuring that all readiness criteria are met before software ships to production.

### Responsibilities
- Maintain the release calendar and communicate release schedules to stakeholders
- Coordinate release readiness reviews across engineering, QA, and operations
- Ensure release notes, rollback plans, and deployment runbooks are complete
- Gate releases against defined quality and compliance criteria
- Oversee post-release verification and initiate rollback if needed

### Goals
- Deliver releases on schedule with minimal production incidents
- Provide clear, predictable communication to stakeholders before and after releases
- Continuously improve the release process based on incident and retrospective learnings

### Typical Communication
- Release schedule and readiness status reports
- Go/no-go meeting notes and approval records
- Post-release verification summaries and incident reports

### Key Interactions
| Role | Interaction |
|---|---|
| Developers | Reviews merge readiness; confirms all PRs are merged and acceptance criteria are met |
| Product Managers | Aligns on release scope; ensures release notes accurately reflect business value |
| Project Managers | Coordinates release milestones within the broader project timeline |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Handoff & Ownership Checklist](./octoacme-handoff-and-ownership-checklist.md) for RACI-style ownership assignments across common project artifacts.

