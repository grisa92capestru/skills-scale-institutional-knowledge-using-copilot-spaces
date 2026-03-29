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
The Scrum Master helps the team adopt and follow Agile practices. They focus on process health, remove impediments, and enable the team to deliver predictably.

### Responsibilities
- Facilitate Agile ceremonies: daily standups, sprint planning, sprint reviews, and retrospectives
- Remove blockers and shield the team from unplanned external interruptions
- Coach the team on Agile principles and continuous improvement practices
- Identify and address process inefficiencies
- Support the Project Manager and Product Manager in maintaining a healthy delivery flow

### Goals
- Maximize team velocity and predictability
- Ensure ceremonies are productive and time-boxed
- Foster a culture of continuous improvement

### Typical Communication
- Daily standups and retrospective facilitation
- Blocker/impediment tracking and escalation
- Process health check-ins with the Project Manager and Product Manager

### Interactions with Existing Roles
- **Project Manager:** Partners closely to align on delivery cadence, risk escalation, and team coordination; the Scrum Master focuses on team-level process while the PM owns external stakeholder communications and timeline reporting.
- **Product Manager:** Supports backlog refinement and sprint planning so the PdM's priorities flow predictably into delivery.
- **Developers:** Acts as a servant-leader, removing obstacles so developers can focus on implementation and quality.

---

## UI/UX Designer

### Role Summary
UI/UX Designers craft user experiences and interfaces that meet customer needs and business goals. They ensure design considerations are integrated early and iterated on throughout the project lifecycle.

### Responsibilities
- Conduct user research and translate insights into design decisions
- Create wireframes, prototypes, and high-fidelity designs
- Define and maintain design standards and component guidelines
- Participate in backlog refinement, sprint planning, and demos
- Collaborate with Developers to ensure designs are implemented accurately

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce rework by surfacing design requirements before implementation begins
- Align design decisions with product outcomes and user needs

### Typical Communication
- Design reviews and prototype walkthroughs with Product Manager and Developers
- Participation in sprint planning and backlog refinement
- Design documentation and annotated mockups in shared project tooling

### Interactions with Existing Roles
- **Product Manager:** Partners on translating user research and product vision into design priorities; participates in roadmap discussions.
- **Developers:** Provides detailed design specifications and works side-by-side during implementation to clarify intent and review fidelity.
- **Project Manager:** Ensures design milestones are accounted for in the project timeline and that handoff dependencies are visible.

---

## Release Manager

### Role Summary
The Release Manager coordinates the end-to-end release process—from readiness validation to post-deploy verification—ensuring releases are safe, predictable, and well-communicated.

### Responsibilities
- Own and maintain the release schedule and release readiness checklist
- Coordinate release activities across Developers, QA, and Operations
- Manage rollback plans and communicate release status to stakeholders
- Ensure all pre-release criteria are met before deployment is triggered
- Conduct post-release reviews and capture lessons learned

### Goals
- Deliver releases on schedule with minimal risk and disruption
- Maintain clear rollback and mitigation plans for every release
- Ensure stakeholders are informed before, during, and after deployments

### Typical Communication
- Release readiness reviews with the project team
- Stakeholder announcements and release notes
- Post-deploy status updates and incident summaries (if applicable)

### Interactions with Existing Roles
- **Project Manager:** Works together on release timing and milestone alignment; the PM owns the project timeline while the Release Manager owns release execution.
- **Developers / QA:** Confirms that all PRs are merged, tests pass, and acceptance criteria are met before triggering the release pipeline.
- **Product Manager:** Coordinates release notes and stakeholder communications to align with product messaging.

See also: [Role Handoff Checklist](octoacme-role-handoff-checklist.md) for release phase ownership.

---

## Data Analyst

### Role Summary
Data Analysts define, track, and report on project and product success metrics. They turn raw data into actionable insights that guide prioritization and continuous improvement.

### Responsibilities
- Partner with the Product Manager and Project Manager to define KPIs and success metrics during project initiation
- Build and maintain dashboards and reports to track progress against goals
- Analyze trends, surface anomalies, and communicate findings to stakeholders
- Support retrospectives with data-backed insights
- Ensure data instrumentation needs are captured as requirements for Developers

### Goals
- Ensure every project has measurable outcomes from day one
- Provide timely, accurate data that informs decision-making
- Connect delivery metrics to business outcomes

### Typical Communication
- Metric reviews in weekly delivery syncs and retrospectives
- Dashboard links and data summaries in stakeholder updates
- Instrumentation requirements added to the backlog as user stories

### Interactions with Existing Roles
- **Product Manager:** Collaborates on success metric definitions and validates that product changes move the right numbers.
- **Project Manager:** Provides execution metrics (velocity, burndown, defect rates) to support status reporting and risk identification.
- **Developers:** Captures instrumentation and data logging requirements so that analytics are built in, not bolted on.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For cross-role handoff guidance, see [Role Handoff Checklist](octoacme-role-handoff-checklist.md).

