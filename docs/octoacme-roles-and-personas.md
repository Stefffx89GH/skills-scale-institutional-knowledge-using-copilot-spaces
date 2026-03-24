# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

For a full mapping of activities to role ownership, see [Role Interactions & RACI](./octoacme-role-interactions-and-raci.md).

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

### Interactions with Existing Roles
- **Project Manager**: Provide progress updates, flag blockers, and participate in planning and retrospectives.
- **Product Manager**: Clarify acceptance criteria, raise technical constraints, and review feature specs.
- **Tech Lead/Architect**: Follow coding standards, escalate technical blockers, and participate in design reviews.
- **QA Analyst**: Hand off completed work for testing, address bug reports promptly.
- **UX Designer**: Implement designs faithfully, raise feasibility concerns early.

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

### Interactions with Existing Roles
- **Project Manager**: Align on scope, timeline, and priorities; surface trade-offs together.
- **Developers**: Define and clarify acceptance criteria; review delivered features against success metrics.
- **UX Designer**: Co-define user requirements and validate design solutions against product goals.
- **Business Analyst**: Review and approve requirements documentation; collaborate on stakeholder interviews.
- **Customer Support/Success**: Gather customer feedback and pain points to inform backlog priorities.

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

### Interactions with Existing Roles
- **Product Manager**: Align on priorities and scope changes; jointly manage stakeholder expectations.
- **Developers**: Remove blockers, track progress, and facilitate planning and retrospectives.
- **Tech Lead/Architect**: Incorporate technical risks into the risk register; validate milestone feasibility.
- **QA Analyst**: Coordinate QA sign-off gates and track defects against release criteria.
- **Business Analyst**: Ensure requirements are documented and traceable to project goals.

---

## UX Designer

### Role Summary
UX Designers translate product requirements into intuitive user experiences. They create wireframes, prototypes, and design specifications that guide development and ensure products meet user needs.

### Responsibilities
- Create wireframes, mockups, and interactive prototypes
- Conduct and synthesize usability research and testing
- Define user journeys and interaction patterns
- Maintain and evolve the design system and component library
- Collaborate on acceptance criteria for UX-sensitive stories

### Goals
- Ensure delivered features are usable, accessible, and consistent
- Reduce rework caused by late-stage UX issues
- Validate designs with real users before and after development

### Typical Communication
- Design reviews and critique sessions
- Annotated design files shared with developers and QA
- Usability test reports and synthesis documents

### Interactions with Existing Roles
- **Project Manager**: Flag design dependencies and timelines; participate in planning to surface UX risks.
- **Product Manager**: Co-define user requirements; validate designs against product vision and success metrics.
- **Developers**: Provide design specifications and assets; resolve implementation questions during development.
- **QA Analyst**: Share acceptance criteria for UX flows; review QA findings for design-related defects.
- **Customer Support/Success**: Use support feedback to identify usability gaps and inform design decisions.

---

## Tech Lead / Architect

### Role Summary
The Tech Lead or Architect sets the technical direction for the project. They make key architectural decisions, coach developers, and ensure the solution is scalable, maintainable, and aligned with broader engineering standards.

### Responsibilities
- Define and document the technical architecture and key design decisions
- Establish coding standards, patterns, and review practices
- Coach and mentor developers; conduct technical design reviews
- Identify and mitigate technical risks early in the lifecycle
- Act as escalation point for complex technical decisions or blockers

### Goals
- Deliver a robust, maintainable architecture that meets both current and future needs
- Reduce technical debt and increase team engineering confidence
- Ensure alignment between technical decisions and product/business goals

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Code and design review feedback
- Technical updates during planning and sprint reviews

### Interactions with Existing Roles
- **Project Manager**: Surface technical risks for the risk register; validate feasibility of proposed timelines and milestones.
- **Product Manager**: Translate product requirements into technical scope; advise on trade-offs and technical constraints.
- **Developers**: Provide technical guidance, review designs and pull requests, and unblock complex issues.
- **QA Analyst**: Define testability requirements and support test strategy for complex components.
- **Business Analyst**: Review technical implications of business requirements and flag constraints.

---

## Business Analyst

### Role Summary
Business Analysts bridge communication between business stakeholders and the delivery team. They gather, document, and validate requirements to ensure the solution addresses real business problems.

### Responsibilities
- Elicit and document business and functional requirements
- Facilitate stakeholder workshops and requirements reviews
- Produce process flow diagrams, use cases, and user stories
- Trace requirements through to acceptance criteria and test cases
- Support sign-off and change management processes

### Goals
- Produce clear, testable requirements that reduce ambiguity
- Ensure the delivered solution meets stated business objectives
- Minimize scope creep through rigorous requirements management

### Typical Communication
- Requirements documents, user stories, and process diagrams
- Workshops and interviews with stakeholders and subject-matter experts
- Regular syncs with Product Manager and development team

### Interactions with Existing Roles
- **Project Manager**: Provide requirements status updates; flag scope changes that may affect timeline or resources.
- **Product Manager**: Align on business requirements and priorities; jointly own the backlog definition.
- **Developers**: Clarify requirements and acceptance criteria; answer questions during development.
- **QA Analyst**: Ensure test cases trace to requirements; collaborate on acceptance testing.
- **Tech Lead/Architect**: Review technical constraints that affect requirements; validate solution design against business needs.

---

## QA Analyst

### Role Summary
QA Analysts design and execute test strategies to verify that features meet acceptance criteria and quality standards. They are a distinct quality gate separate from the developer testing responsibilities.

### Responsibilities
- Develop and maintain test plans, test cases, and automation scripts
- Execute functional, regression, and exploratory testing
- Track and manage defects through to resolution
- Verify quality gates are met before release sign-off
- Contribute to the Definition of Done and acceptance criteria

### Goals
- Ensure releases meet quality standards and are free of critical defects
- Increase test coverage and reduce the cost of defect detection
- Provide clear quality signals to the team throughout the sprint

### Typical Communication
- Test plans and test results reports shared with team
- Defect reports with reproduction steps and severity ratings
- QA sign-off confirmation to PM and Tech Lead before release

### Interactions with Existing Roles
- **Project Manager**: Report test status and defect trends; provide quality sign-off for release gates.
- **Product Manager**: Validate that features meet acceptance criteria and product success metrics.
- **Developers**: Collaborate on testability, triage defects, and verify fixes.
- **Tech Lead/Architect**: Align on test strategy for complex components and integration points.
- **UX Designer**: Validate UX-related acceptance criteria; report design-related defects.

---

## Customer Support / Success

### Role Summary
Customer Support/Success representatives act as the voice of the customer within the project team. They escalate user-reported issues, provide post-launch feedback, and help ensure released features meet real-world user needs.

### Responsibilities
- Escalate customer-reported bugs and pain points to the delivery team
- Provide context on user behavior and common failure scenarios
- Participate in release reviews and retrospectives when customer impact is high
- Maintain and share release notes and internal enablement materials for new features
- Collect and relay post-launch feedback to inform future iterations

### Goals
- Reduce customer-impacting defects reaching production
- Ensure the team understands real-world user impact of decisions
- Support customers effectively through feature transitions

### Typical Communication
- Bug and feedback reports routed to PM or PM board
- Participation in release readiness reviews and retrospectives
- Internal enablement docs and release announcements

### Interactions with Existing Roles
- **Project Manager**: Report customer-impacting issues and participate in release readiness reviews.
- **Product Manager**: Share customer feedback and usage patterns to influence backlog prioritization.
- **Developers**: Provide detailed reproduction steps for customer-reported defects.
- **QA Analyst**: Flag edge cases identified through customer support channels for inclusion in test plans.
- **UX Designer**: Share usability observations from customer interactions to inform design improvements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Interactions & RACI](./octoacme-role-interactions-and-raci.md) for a full activity-to-role ownership mapping.

