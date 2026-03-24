# OctoAcme Project Management Docs

Welcome! This README is the central index for all OctoAcme project management process documents. Use it as your starting point to find guidance, templates, and best practices for planning and delivering projects.

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle designed to deliver customer value iteratively while maintaining clear ownership and strong team alignment. Projects move through five phases: **Initiation** (define the problem, stakeholders, success metrics, and a go/no-go decision), **Planning** (convert the initiative into an actionable backlog and release plan), **Execution** (build and track progress through defined workflows), **Release** (deploy with standardized safeguards), and **Retrospective/Continuous Improvement** (capture learnings and feed improvements back into future work). Key artifacts used throughout include a Project One-pager/Charter, a prioritized backlog with acceptance criteria, a Definition of Done, a risk register, and retrospective action items.

Roles are intentionally explicit to reduce ambiguity and single-person dependencies. A **Project Manager (PM)** coordinates delivery mechanics—timeline, risks, dependencies, and communications—while a **Product Manager (PdM)** defines outcomes, prioritizes work, and measures impact. **Developers** implement features with an emphasis on maintainability and testability, participate in estimation and reviews, and surface technical risks early. **QA/Testing** validates work against acceptance criteria, and **Stakeholders** provide inputs and approvals at defined checkpoints (planning, milestone reviews, releases).

Day-to-day execution relies on a predictable team rhythm and a simple workflow board. OctoAcme uses regular ceremonies—daily standups for blockers and dependencies, weekly delivery syncs for progress and risks, and end-of-sprint demos—paired with a shared project board that tracks work from Backlog → Ready → In Progress → In Review → QA → Done. Communication emphasizes a "single source of truth" for status, structured updates using templates (weekly status updates, incident communications), and a clear escalation path: team triage → PM escalation → Product Lead/dependent teams → sponsor-level when business impact is high.

Quality assurance is built into both execution and release practices. During development, OctoAcme expects unit tests for new logic, integration tests where needed, and end-to-end smoke tests for critical flows—supported by CI-based automated tests, linting, and security scanning before merging. PRs are kept small when possible, tied to issues and acceptance criteria, and require at least one approval before merge. Releases follow a standardized checklist (acceptance criteria met, scans passing, release notes drafted), staged deployments with staging smoke tests before production, post-deploy verification, stakeholder announcements, and a rollback/incident playbook, all followed by retrospectives that convert lessons learned into owned, time-bound action items.

## Main Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

- **Starting a new project?** Begin with the [Project Initiation Guide](octoacme-project-initiation.md) to set up your project charter and define success criteria.
- **Planning a sprint or release?** Use the [Project Planning](octoacme-project-planning.md) and [Execution & Tracking](octoacme-execution-and-tracking.md) docs as your guide for backlog grooming, estimation, and board management.
- **Managing risks?** Keep your risk register updated and follow the escalation paths outlined in [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Preparing to ship?** Follow the release checklist in [Release & Deployment Guide](octoacme-release-and-deployment.md) and ensure all acceptance criteria are met before deploying.
- **After a release?** Run a retrospective using the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide to capture learnings and create action items.
- **Clarifying responsibilities?** Refer to [Roles & Personas](octoacme-roles-and-personas.md) for a clear breakdown of each team member's accountabilities.
