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

## Technical / Engineering Leads

### Role Summary
Technical or Engineering Leads guide technical decisions and coordinate engineering work for a project or workstream. They provide technical leadership and do not necessarily manage people.

### Responsibilities
- Guide architecture, technical design, and integration decisions
- Coordinate technical estimates, implementation sequencing, and engineering dependencies
- Identify technical risks and propose mitigations
- Support Developers with design decisions, reviews, and technical blockers

### Goals
- Deliver a coherent, maintainable technical solution
- Make technical trade-offs visible early
- Help the team deliver safely and predictably

### Typical Communication
- Design discussions and technical decision records
- Planning and dependency reviews with engineering
- Technical risk updates during delivery syncs

### Interactions with Existing Roles
- Works with Developers on implementation choices, code quality, and technical blockers
- Partners with the Product Manager (PdM) to assess feasibility and explain technical trade-offs against product outcomes
- Shares estimates, dependencies, and technical risks with the Project Manager (PM) for planning and risk tracking
- Coordinates with QA/Testing and the Operations / SRE / Release Lead on testability and operational requirements

---

## UX / Product Designers

### Role Summary
UX or Product Designers research user needs and shape accessible, usable product experiences that support the intended outcomes.

### Responsibilities
- Plan or conduct user research and synthesize user needs
- Create and validate user flows, interaction designs, and prototypes
- Identify usability and accessibility considerations
- Document design decisions and user-facing acceptance details

### Goals
- Ensure solutions address user needs
- Make experiences clear, usable, and accessible
- Reduce avoidable rework through early design validation

### Typical Communication
- Design reviews, prototypes, and research findings
- Product discovery and backlog refinement
- Collaboration with engineering and QA/Testing during implementation

### Interactions with Existing Roles
- Partners with the PdM and stakeholders to understand users, validate problem framing, and align designs with product outcomes
- Works with Developers and the Technical / Engineering Lead to assess feasibility and resolve design-implementation trade-offs
- Collaborates with QA/Testing on user-facing acceptance criteria and usability validation
- Keeps the PM informed of design decisions or research findings that affect scope, dependencies, or milestones

---

## QA / Test Leads

### Role Summary
A QA / Test Lead coordinates the project's quality approach and makes test coverage and readiness visible. This lead role complements the broader QA/Testing responsibility; it does not replace Developers' responsibility to test their work or the team's quality practices.

### Responsibilities
- Define a risk-based test strategy with the team
- Coordinate test coverage across unit, integration, and end-to-end testing as applicable
- Clarify acceptance validation and identify quality gaps or release blockers
- Communicate test results, risks, and readiness status

### Goals
- Find important defects early and reduce release risk
- Ensure acceptance criteria are verifiable
- Provide a clear, evidence-based view of quality and readiness

### Typical Communication
- Test plans, defect reports, and quality status updates
- Acceptance-criteria reviews during planning
- Release-readiness reviews with delivery and operations roles

### Interactions with Existing Roles
- Works with Developers on testability, test coverage, and defect resolution
- Partners with the PdM to make acceptance criteria clear and confirm the intended behavior
- Reports quality risks and readiness gaps to the PM for plans and status updates
- Coordinates with the Operations / SRE / Release Lead on smoke tests and post-deployment verification

---

## Security / Privacy Leads

### Role Summary
Security or Privacy Leads help the team identify and address security, privacy, and compliance needs throughout delivery. They advise and coordinate with the appropriate specialists and do not replace formal security incident or review processes.

### Responsibilities
- Identify applicable security and privacy requirements, risks, and review needs
- Coordinate threat modeling, privacy reviews, and mitigation tracking where appropriate
- Advise on secure design, data handling, and escalation paths
- Confirm that security and privacy risks and decisions are documented

### Goals
- Address security and privacy risks early
- Make risk ownership and mitigations clear
- Support safe releases and appropriate incident escalation

### Typical Communication
- Security and privacy reviews and risk-register updates
- Design and release-readiness discussions
- Escalation to Security or Privacy specialists and on-call contacts as required

### Interactions with Existing Roles
- Partners with Developers and the Technical / Engineering Lead to incorporate secure design and implementation practices
- Works with the PM to document risk owners, mitigations, dependencies, and escalation needs
- Aligns with the PdM and stakeholders on privacy impacts and risk-based product decisions
- Coordinates with the QA / Test Lead and Operations / SRE / Release Lead on security validation and release controls

---

## Data / Analytics Leads

### Role Summary
Data or Analytics Leads ensure project success measures can be observed and that instrumentation and reporting support reliable decisions.

### Responsibilities
- Translate success metrics into measurable events, data requirements, and reporting needs
- Define or review instrumentation and data-quality expectations
- Validate that dashboards or analyses accurately reflect agreed metrics
- Communicate measurement limitations and outcome findings

### Goals
- Make progress and outcomes measurable
- Improve confidence in product and delivery decisions
- Surface data gaps that could undermine evaluation

### Typical Communication
- Metric definitions and instrumentation plans
- Analytics reviews with product and engineering
- Outcome reports and dashboard updates

### Interactions with Existing Roles
- Partners with the PdM to define how product success metrics will be measured and interpreted
- Works with Developers and the Technical / Engineering Lead on instrumentation and data collection
- Shares measurement status, data limitations, and findings with the PM for progress and outcome reporting
- Consults stakeholders on reporting needs while respecting security and privacy requirements

---

## Operations / SRE / Release Leads

### Role Summary
Operations, Site Reliability Engineering (SRE), or Release Leads coordinate the operational readiness and safe deployment of a project. The specific title depends on team structure.

### Responsibilities
- Define operational readiness needs, including monitoring, alerting, and support handoff
- Coordinate deployment, rollback, and mitigation planning
- Prepare or review smoke tests and post-deployment verification
- Surface reliability risks and coordinate incident response with the appropriate on-call roles

### Goals
- Make releases observable and recoverable
- Reduce deployment and operational risk
- Ensure support teams can operate and respond to the delivered service

### Typical Communication
- Release plans and readiness reviews
- Monitoring and runbook updates
- Incident and post-deployment status communications

### Interactions with Existing Roles
- Works with Developers and the Technical / Engineering Lead on reliability, deployment, and rollback requirements
- Partners with the QA / Test Lead on smoke tests and verification plans
- Coordinates with the PM on release schedules, dependencies, risks, and stakeholder communications
- Aligns with the Security / Privacy Lead on operational security needs and with stakeholders or support teams on handoff and service expectations

---

## Assigning and Combining Roles

These personas describe responsibilities, not mandatory job titles or additional headcount. A person may hold more than one role on a smaller project, but the team should explicitly assign an accountable owner for each responsibility that applies. Teams should involve specialized roles according to project risk, complexity, and applicable requirements, and document key decisions, dependencies, and handoffs in the existing project artifacts.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
