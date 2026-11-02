# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Roles may be combined or titled differently across teams, especially on smaller projects. Regardless of staffing, make ownership and handoffs explicit.

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

## Technical Leads / Engineering Leads

### Role Summary
Technical Leads guide engineering decisions and ensure the solution is maintainable, secure, and aligned with product needs. They provide technical direction without replacing the delivery coordination owned by the Project Manager or product prioritization owned by the Product Manager.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Coordinate technical estimates, implementation sequencing, and engineering dependencies
- Surface technical risks and propose mitigations
- Support Developers through design reviews, problem-solving, and coaching
- Confirm technical readiness and communicate trade-offs

### Goals
- Deliver a reliable, maintainable solution that meets agreed requirements
- Make technical decisions visible and resolve engineering blockers early

### Typical Communication
- Design docs, architecture reviews, and code reviews
- Technical risk and dependency updates in planning and delivery syncs

### Interactions with Existing Roles
- Partner with Developers on implementation choices, reviews, and technical growth
- Work with the Product Manager to clarify feasibility and scope trade-offs
- Give the Project Manager estimates, dependency updates, and risk information for plans and status reports
- Coordinate with QA / Test Leads on testability and technical quality requirements

---

## QA / Test Leads

### Role Summary
QA / Test Leads define how the team will verify that a delivery meets acceptance criteria and quality expectations. They coordinate validation and make quality risks visible; they do not take sole responsibility for quality away from the whole team.

### Responsibilities
- Shape the test strategy and coordinate appropriate unit, integration, and end-to-end coverage
- Review acceptance criteria for testability and identify gaps
- Coordinate functional, regression, accessibility, and release validation as applicable
- Track defects, quality risks, and test results, and recommend readiness actions

### Goals
- Provide timely evidence that the solution meets agreed acceptance criteria
- Detect important defects and quality risks before release

### Typical Communication
- Test plans, defect reports, and release-readiness updates
- QA coordination with Developers during implementation and delivery

### Interactions with Existing Roles
- Collaborate with Developers and Technical Leads to build testability and address defects
- Work with the Product Manager and stakeholders to clarify acceptance criteria and expected behavior
- Coordinate with the Project Manager on test dependencies, timelines, blockers, and status
- Partner with UX / Product Designers to validate usability and accessibility where applicable

---

## UX / Product Designers

### Role Summary
UX / Product Designers translate user needs into clear, usable, and accessible experiences. They inform product decisions with research and design and collaborate with engineering and QA through implementation and validation.

### Responsibilities
- Conduct or synthesize user research and identify user needs
- Create interaction flows, prototypes, and design specifications
- Validate usability and accessibility and incorporate feedback
- Communicate design constraints, rationale, and open questions

### Goals
- Ensure delivered experiences solve user problems and are understandable and usable
- Reduce rework by aligning design and implementation early

### Typical Communication
- Research findings, design reviews, prototypes, and design-system documentation
- Ongoing design handoffs and implementation feedback with engineering

### Interactions with Existing Roles
- Partner with the Product Manager to connect user needs, product outcomes, and priorities
- Work with Developers and Technical Leads to assess feasibility and implement designs consistently
- Coordinate with QA / Test Leads on usability and accessibility checks
- Share research and design decisions with the Project Manager to support planning and stakeholder updates

---

## DevOps / Release Leads

### Role Summary
DevOps / Release Leads coordinate the environments, deployment practices, and operational readiness needed to release and support a change safely.

### Responsibilities
- Maintain or coordinate deployment pipelines, environments, and release procedures
- Confirm monitoring, alerting, and operational ownership are ready for deployment
- Prepare rollback or mitigation plans with the delivery team
- Communicate release requirements, deployment status, and operational risks

### Goals
- Make releases repeatable, observable, and recoverable
- Reduce deployment risk and improve post-release stability

### Typical Communication
- Release plans, deployment checklists, operational dashboards, and incident channels
- Readiness and post-deployment updates with delivery and support stakeholders

### Interactions with Existing Roles
- Coordinate with Technical Leads and Developers on build, deployment, and infrastructure needs
- Work with QA / Test Leads to align smoke tests and release validation
- Partner with the Project Manager on release timing, dependencies, risk tracking, and communications
- Align with the Product Manager on the scope and customer impact of a release

---

## Security / Privacy Leads

### Role Summary
Security / Privacy Leads advise the team on protecting systems and data, identifying risks, and meeting applicable security and privacy requirements. They help teams plan appropriate controls and reviews; delivery teams remain responsible for implementing agreed mitigations.

### Responsibilities
- Identify security and privacy risks, requirements, and review checkpoints
- Advise on appropriate controls, data handling, and risk mitigations
- Coordinate security or privacy reviews and track findings to resolution or explicit risk acceptance
- Escalate material risks through the agreed incident and governance paths

### Goals
- Identify and address material security and privacy risks before release
- Make security and privacy responsibilities and decisions clear to the team

### Typical Communication
- Risk assessments, review findings, mitigation plans, and incident escalations
- Security and privacy updates during planning and release-readiness reviews

### Interactions with Existing Roles
- Work with Technical Leads and Developers to design and implement mitigations
- Coordinate with QA / Test Leads on verification of relevant controls
- Advise the Product Manager on user, data, and product trade-offs
- Keep the Project Manager informed of review dependencies, risks, and escalations for planning and stakeholder communication

---

## Executive Sponsors / Business Owners

### Role Summary
Executive Sponsors / Business Owners provide strategic direction, sponsorship, and timely decisions when a project needs business-level alignment or escalation. They do not replace the Product Manager's day-to-day product prioritization or the Project Manager's delivery coordination.

### Responsibilities
- Confirm strategic alignment and expected business outcomes
- Secure or advocate for the resources and cross-team support needed
- Resolve escalated priority, scope, or organizational conflicts
- Review progress, material risks, and outcome measures at agreed checkpoints

### Goals
- Ensure the initiative remains aligned with organizational priorities
- Enable timely decisions and remove barriers that exceed the delivery team's authority

### Typical Communication
- Milestone reviews, decision requests, and concise status and risk updates
- Escalations and outcome reviews with project and product leadership

### Interactions with Existing Roles
- Align with the Product Manager on intended outcomes, priority, and changes in business context
- Receive delivery status, dependencies, and escalations from the Project Manager
- Support the team by resolving cross-team or resource barriers raised by the PM or Product Manager
- Provide direction without bypassing the agreed product and delivery decision-making responsibilities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
