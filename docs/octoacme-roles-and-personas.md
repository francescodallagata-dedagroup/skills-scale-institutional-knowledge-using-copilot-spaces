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

## QA / Testing

(Existing QA responsibilities — validate quality and acceptance criteria)

---

## Stakeholders

(Existing content)

---

## New / Expanded Personas (proposed additions)

These personas reflect common but previously under-described functions that influence project outcomes. Add them to the canonical roles doc to improve clarity and accountability.

### Business Analyst (BA)
- Responsibilities:
  - Elicit and document requirements from stakeholders and users.
  - Map business processes and identify gaps or improvement opportunities.
  - Translate business needs into clear user stories and acceptance criteria.
  - Support acceptance testing and validate delivered outcomes against business scenarios.
- Interactions:
  - Works with PdM to refine scope and success criteria.
  - Partners with PM and Developers during planning to ensure requirements are actionable.
  - Engages stakeholders and Customer Advocate to validate assumptions and outcomes.

### DevOps Engineer
- Responsibilities:
  - Design, build, and maintain CI/CD pipelines, automation, and infrastructure-as-code.
  - Improve deployment reliability, observability, and recovery processes.
  - Collaborate on production readiness, capacity planning, and runbooks.
- Interactions:
  - Works with Developers to enable smooth release processes and testing automation.
  - Supports PM and QA with deployment schedules, rollback plans, and post-release verification.
  - Escalates operational risks to PM and Product Lead when release or infra constraints affect timelines.

### UX Designer
- Responsibilities:
  - Lead user research, design user flows, wireframes, and high-fidelity interfaces.
  - Validate usability through testing and iterate designs based on feedback.
  - Produce assets and design specifications for engineering implementation.
- Interactions:
  - Collaborates with PdM to ensure product decisions align with user needs.
  - Works with Developers to clarify implementation details and acceptance criteria for UI/UX.
  - Partners with Customer Advocate and BA for research and validation activities.

### Executive Sponsor
- Responsibilities:
  - Provide strategic guidance and ensure alignment with broader organizational objectives.
  - Approve budgets and major scope decisions; support escalation for business-critical issues.
  - Champion the project at leadership forums to remove cross-organizational blockers.
- Interactions:
  - Engages periodically with PM and PdM for milestone reviews and major decisions.
  - Is looped in by PM for Level-3 escalations and significant risk/constraint discussions.

### Customer Advocate (User Research / Support Liaison)
- Responsibilities:
  - Represent customer voice across discovery and delivery phases.
  - Collect, synthesize, and communicate user feedback to PdM and UX.
  - Help validate user impact of proposed changes and post-release satisfaction.
- Interactions:
  - Works closely with PdM, UX, BA, and QA to ensure user feedback shapes priorities and acceptance.
  - Partners with Support and Sales to surface real-world issues and trends.
  - Participates in demos or feedback sessions where appropriate.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Guidelines for adding new personas
- Define a short Role Summary (1–2 sentences).
- List clear Responsibilities (3–6 bullets).
- State Typical Goals (1–3 bullets).
- Describe Typical Communication and Interactions with existing roles.
- Record where this role is expected to appear in project artifacts (e.g., owner of risk, reviewer of designs, on-call).
