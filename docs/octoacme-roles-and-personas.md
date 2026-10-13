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

## New Personas (Proposed additions)

The following personas are proposed to improve clarity, ownership, and cross-functional coordination. Each entry includes a brief role summary, responsibilities, and how the persona typically interacts with existing roles.

### Release / Platform Engineer

Role Summary: Owns release pipelines, deployment automation, environment hygiene, and rollback procedures.

Responsibilities:
- Design, maintain, and operate CI/CD pipelines and release automation
- Define and test rollback and mitigation procedures
- Maintain staging and production environment hygiene and deployment runbooks
- Coordinate release windows and deployment approvals when required

Interactions:
- Works closely with Developers on build artifacts and deployment configurations
- Coordinates with QA Lead to ensure pre-release test coverage and gating
- Partners with Project Manager for scheduling and with SRE/on-call for incident response

### UX Researcher / Design Lead

Role Summary: Responsible for customer research, usability testing, accessibility checks, and design guidance that ensures features meet user needs.

Responsibilities:
- Conduct user interviews, usability tests, and heuristic reviews
- Define UX acceptance criteria and accessibility requirements
- Provide design assets and specifications to Developers
- Advocate for user-centered decisions in prioritization

Interactions:
- Partners with Product Managers to define success criteria and user-facing requirements
- Provides Developers and QA with acceptance criteria and test scenarios related to UX
- Works with Project Manager to schedule research and design reviews during planning

### Data / Measurement Lead

Role Summary: Defines metrics, instrumentation, dashboards, and experiment analysis to measure outcomes and inform product decisions.

Responsibilities:
- Specify event schemas and instrumentation requirements for features
- Create and maintain dashboards and alerts for success metrics
- Analyze experiment and A/B test results and report findings
- Ensure data quality and access for stakeholders

Interactions:
- Collaborates with Product Managers to set measurable success metrics
- Provides Developers with event specs and with QA guidance on telemetry checks
- Shares findings with stakeholders and helps prioritize follow-up work

### Security & Compliance Lead

Role Summary: Ensures features meet security standards and compliance requirements through threat modeling, security reviews, and coordination of scans.

Responsibilities:
- Conduct threat models and security reviews during design and pre-release
- Define compliance requirements and checklist items for releases
- Coordinate security tool scans and triage findings
- Escalate critical security risks to Product Manager and Project Manager

Interactions:
- Reviews technical designs with Developers and flags required mitigations
- Communicates blockers and risk mitigations to Project Manager and Product Manager
- Works with Release/Platform Engineer on secure deployment practices

### Customer Success / Support Liaison

Role Summary: Acts as the bridge between customers/support and the delivery team, bringing real-user feedback and guiding rollout communications.

Responsibilities:
- Surface customer feedback, feature requests, and production pain points
- Validate acceptance with real users during beta or pilot phases
- Coordinate release communications, enablement materials, and support runbooks
- Help prioritize issues raised by customers post-release

Interactions:
- Works with Product Managers to validate priorities and with QA to define real-user acceptance tests
- Collaborates with Developers for triaging production issues and with Project Manager for rollout timing
- Shares customer-impacting information with stakeholders and support teams

### QA Lead / Test Engineering

Role Summary: Defines the test strategy, automation approach, and release readiness gating to ensure quality at scale.

Responsibilities:
- Define end-to-end and integration testing strategies and ownership
- Maintain automation suites and measure coverage for critical flows
- Define release readiness criteria and participate in pre-release gating
- Work with Developers to improve testability and observability

Interactions:
- Coordinates with Developers on test plans, mocks, and deterministic test data
- Works with Release/Platform Engineer on integrating test runs into CI/CD pipelines
- Communicates blocking issues and test results to Project Manager and Product Manager

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
