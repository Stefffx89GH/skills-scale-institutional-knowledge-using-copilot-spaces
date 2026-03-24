# OctoAcme — Release Readiness Checklist

## Purpose
Confirm that all roles have completed their pre-release responsibilities before a feature or product release proceeds to production.

**Related:** [Roles & Personas](./octoacme-roles-and-personas.md) · [RACI](./octoacme-role-interactions-and-raci.md) · [Release & Deployment Guide](./octoacme-release-and-deployment.md)

---

## Engineering & Quality

| # | Item | Owner | Done? |
|---|---|---|---|
| 1 | All acceptance criteria met and verified | QA Analyst | [ ] |
| 2 | All PRs merged and feature branches cleaned up | Developers | [ ] |
| 3 | CI pipeline passing (tests, lint, security scans) | Tech Lead / Architect | [ ] |
| 4 | Regression test suite executed; no open critical/high defects | QA Analyst | [ ] |
| 5 | Performance / load testing completed (if applicable) | QA Analyst + Developers | [ ] |
| 6 | Security scanning clean; findings triaged and documented | Tech Lead / Architect | [ ] |
| 7 | Rollback or mitigation plan documented | Tech Lead / Architect | [ ] |
| 8 | Smoke test plan prepared for post-deployment | QA Analyst | [ ] |

---

## Product & Design

| # | Item | Owner | Done? |
|---|---|---|---|
| 1 | Product Manager has reviewed and approved feature delivery against success metrics | Product Manager | [ ] |
| 2 | UX design acceptance criteria verified in staging | UX Designer + QA Analyst | [ ] |
| 3 | Release notes drafted and reviewed | Product Manager | [ ] |
| 4 | Feature flags / progressive rollout plan confirmed (if applicable) | Product Manager + Tech Lead | [ ] |

---

## Documentation & Communication

| # | Item | Owner | Done? |
|---|---|---|---|
| 1 | Release notes finalized and approved | Product Manager | [ ] |
| 2 | Customer-facing documentation updated | Business Analyst / Product Manager | [ ] |
| 3 | Internal enablement materials prepared for Customer Support/Success | Product Manager + Customer Support/Success | [ ] |
| 4 | Stakeholder communication drafted and scheduled | Project Manager | [ ] |
| 5 | On-call / support runbook updated with new feature context | Tech Lead / Architect + Customer Support/Success | [ ] |

---

## Go / No-Go Sign-off

| # | Role | Sign-off | Date |
|---|---|---|---|
| 1 | QA Analyst — quality gate cleared | | |
| 2 | Tech Lead / Architect — technical readiness confirmed | | |
| 3 | Product Manager — business acceptance confirmed | | |
| 4 | Project Manager — release approved to proceed | | |
| 5 | Customer Support/Success — prepared to support release | | |

---

## Post-Release

| # | Item | Owner | Done? |
|---|---|---|---|
| 1 | Post-deployment smoke tests executed | QA Analyst | [ ] |
| 2 | Release announcement sent to stakeholders | Project Manager | [ ] |
| 3 | Monitoring dashboards reviewed (errors, latency, usage) | Tech Lead / Architect | [ ] |
| 4 | Customer Support/Success notified and enabled | Project Manager | [ ] |
| 5 | Retrospective scheduled (if sprint/milestone release) | Project Manager | [ ] |

---

## Notes
- A release should not proceed without all Go/No-Go sign-offs above.
- Any open critical defects must be resolved or explicitly risk-accepted by the Product Manager before sign-off.
- See [Rollback & Incident Playbook](./octoacme-release-and-deployment.md#rollback--incident-playbook) if issues are found post-deployment.
