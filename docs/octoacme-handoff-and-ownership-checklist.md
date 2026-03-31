# OctoAcme — Handoff & Ownership Checklist

## Purpose
Make responsibilities and handoffs explicit for common project artifacts, reducing ambiguity and preventing items from falling through the cracks.

## How to use this document
- Use the RACI table to confirm ownership before a project phase begins.
- At the start of each phase, review the phase checklist with the relevant personas.
- Update ownership assignments in the table if your project has a different team structure.

**RACI key:**
| Code | Meaning |
|---|---|
| **R** | Responsible — does the work |
| **A** | Accountable — approves/signs off |
| **C** | Consulted — provides input |
| **I** | Informed — kept in the loop |

---

## RACI Matrix — Project Artifacts

| Artifact | Project Manager | Product Manager | Developer | Scrum Master | UX Designer | DevOps Engineer | Business Analyst | Release Manager |
|---|---|---|---|---|---|---|---|---|
| Project Charter / One-pager | A | R | C | I | C | I | C | I |
| Product Roadmap | C | A/R | C | I | C | I | C | I |
| Sprint/Iteration Backlog | C | A | R | R | C | I | C | I |
| Acceptance Criteria | C | A | C | I | C | I | R | I |
| Risk Register | A/R | C | C | C | I | C | C | I |
| Architecture / Technical Design | I | C | A/R | I | I | C | I | I |
| UX Wireframes & Prototypes | I | C | C | I | A/R | I | C | I |
| Release Notes | C | A | C | I | I | C | C | R |
| Deployment Plan | A | I | C | I | I | R | I | A |
| Comms Plan (stakeholder messaging) | A/R | C | I | I | I | I | C | C |
| Post-release Verification Report | C | I | C | I | I | R | I | A/R |
| Retrospective Action Items | A | C | C | R | C | C | C | I |

---

## Phase Checklists

### Initiation
- [ ] Project Charter / One-pager drafted and reviewed (PM + PdM + BA)
- [ ] Stakeholders identified and roles confirmed
- [ ] High-level risks documented in Risk Register (PM)
- [ ] Initial roadmap alignment confirmed (PdM)

### Planning
- [ ] Sprint backlog populated and estimated (Dev + Scrum Master + PdM)
- [ ] Acceptance criteria written for all stories in scope (BA + PdM)
- [ ] UX wireframes completed and reviewed before development starts (UX Designer)
- [ ] Infrastructure and environment requirements confirmed (DevOps Engineer)
- [ ] Risk Register reviewed and mitigations assigned (PM)
- [ ] Comms plan drafted for stakeholder updates (PM)

### Execution
- [ ] Daily standups facilitated and impediments logged (Scrum Master)
- [ ] Design handoff notes provided to developers (UX Designer)
- [ ] CI/CD pipelines operational and builds passing (DevOps Engineer)
- [ ] Requirements clarifications tracked and reflected in stories (BA)
- [ ] Sprint reviews held with stakeholders (PM + PdM)

### Release
- [ ] All acceptance criteria met and PRs merged (Developer + BA)
- [ ] Release notes drafted and reviewed (Release Manager + PdM)
- [ ] Deployment plan finalized with rollback steps (DevOps Engineer + Release Manager)
- [ ] Go/no-go meeting completed with sign-off (Release Manager + PM)
- [ ] Deployment executed and post-release verification run (DevOps Engineer + Release Manager)
- [ ] Release announcement sent to stakeholders (PM + Release Manager)

### Close & Retrospective
- [ ] Retrospective facilitated and notes captured (Scrum Master)
- [ ] Action items assigned with owners and due dates (PM)
- [ ] Project documentation archived and accessible
- [ ] Learnings shared with broader team (PM + PdM)

---

## Related Documents
- [Roles & Personas](./octoacme-roles-and-personas.md) — detailed descriptions of each role
- [Project Management Overview](./octoacme-project-management-overview.md) — lifecycle and principles
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — release checklist and rollback playbook
