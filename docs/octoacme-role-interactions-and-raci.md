# OctoAcme — Role Interactions & RACI

## Purpose
Map common project activities to role ownership using the RACI model (Responsible, Accountable, Consulted, Informed).

**Key:** R = Responsible · A = Accountable · C = Consulted · I = Informed

Full role definitions are in [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

---

## RACI Matrix

| Activity | Project Manager | Product Manager | Tech Lead / Architect | Developers | UX Designer | Business Analyst | QA Analyst | Customer Support / Success | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|
| **Initiation One-pager** | R | A | C | I | C | C | I | I | C |
| **Backlog Definition** | C | A | C | C | C | R | C | I | I |
| **Sprint Planning** | R | C | C | R | C | C | C | I | I |
| **Architecture Decisions** | I | C | A/R | C | I | C | I | I | I |
| **UX Design & Prototyping** | I | C | C | C | A/R | C | C | I | I |
| **Requirements Documentation** | C | A | C | C | C | R | C | I | I |
| **Risk Register Maintenance** | A/R | C | C | C | I | C | I | I | I |
| **Test Plan & Execution** | I | C | C | C | C | C | A/R | I | I |
| **QA Sign-off** | C | C | C | C | C | C | A/R | I | I |
| **Release Readiness Review** | A | C | C | C | C | C | R | C | I |
| **Deployment** | C | I | C | R | I | I | C | I | I |
| **Stakeholder Communication** | R | C | I | I | I | C | I | C | A |
| **Retrospective Facilitation** | A/R | C | C | C | C | C | C | C | I |
| **Post-launch Feedback Collection** | C | A | I | I | C | C | C | R | I |

---

## Notes
- **R (Responsible)**: Does the work.
- **A (Accountable)**: Ultimately answerable for the outcome; approves the result. Only one A per activity.
- **C (Consulted)**: Provides input before or during the activity; two-way communication.
- **I (Informed)**: Kept up to date on progress/outcomes; one-way communication.
- **A/R**: A single role is both Accountable and does the primary work. Only one A is assigned per activity — combining A and R into the same role is valid when that role both executes and owns the outcome.

---

## Cross-references
- [Roles & Personas](./octoacme-roles-and-personas.md)
- [Project Kickoff Checklist](./octoacme-project-kickoff-checklist.md)
- [Release Readiness Checklist](./octoacme-release-readiness-checklist.md)
- [Project Management Overview](./octoacme-project-management-overview.md)
