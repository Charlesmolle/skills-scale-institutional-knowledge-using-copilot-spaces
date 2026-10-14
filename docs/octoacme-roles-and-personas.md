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

## Project Sponsor / Executive Sponsor

### Role Summary
The Project Sponsor owns strategic authorization and funding for a project. They make major trade-off decisions and remove organizational blockers.

### Responsibilities
- Approve project initiation, funding, and major scope changes
- Make decisions at key decision gates
- Serve as the final escalation point for delivery or business risks
- Remove organizational blockers

### Goals
- Ensure projects align with business strategy
- Keep investment tied to measurable outcomes

### Typical Communication
- Milestone and decision-gate reviews
- Escalation conversations when delivery or outcomes are at risk

### Interactions with Existing Roles
- **Project Managers:** receive status, risk, and escalation reports; confirm decisions at gates.
- **Product Managers:** align on product outcomes, priorities, and funding trade-offs.

---

## Business Analyst

### Role Summary
Business Analysts elicit and document requirements, map workflows, and translate business needs into testable backlog items.

### Responsibilities
- Gather and document requirements from stakeholders
- Map current and future workflows
- Support the definition of acceptance criteria
- Keep requirements traceable to backlog items

### Goals
- Reduce ambiguity before work reaches development
- Ensure requirements reflect real stakeholder needs

### Typical Communication
- Stakeholder interviews and workshops
- Requirements documents and workflow diagrams
- Backlog refinement sessions

### Interactions with Existing Roles
- **Product Managers:** refine problem statements into detailed, testable requirements.
- **Developers and QA:** clarify requirements and acceptance criteria.
- **Stakeholders:** validate that documented needs are accurate.

---

## UX / Design Lead

### Role Summary
The UX / Design Lead represents usability and user experience, guiding design decisions so solutions are usable and accessible.

### Responsibilities
- Define user flows, prototypes, and design standards
- Run or coordinate usability testing
- Ensure accessibility requirements are considered
- Review implemented work against design intent

### Goals
- Deliver intuitive, accessible experiences
- Reduce rework caused by usability issues

### Typical Communication
- Design reviews and prototype walkthroughs
- Usability findings shared with the team

### Interactions with Existing Roles
- **Product Managers:** align designs with product outcomes and user research.
- **Developers:** hand off designs and review implementation.
- **QA:** help validate usability and accessibility acceptance criteria.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect guides technical direction, design decisions, integration points, and technical risk management.

### Responsibilities
- Define and review architecture and design approaches
- Set technical standards and conventions
- Identify and manage technical risks and dependencies
- Support estimation and feasibility assessments

### Goals
- Ensure a viable, maintainable technical solution
- Reduce technical debt and integration surprises

### Typical Communication
- Design reviews and architecture decision records
- Technical guidance in planning and code reviews

### Interactions with Existing Roles
- **Developers:** provide direction and review designs and code.
- **Project Managers:** share technical risks and dependency information.
- **Security / Compliance Lead and Release / Operations Lead:** agree on controls, deployment, and operational needs.

---

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead identifies security, privacy, regulatory, and threat-modeling requirements and ensures required controls and approvals are completed.

### Responsibilities
- Define security and compliance requirements
- Run or coordinate threat modeling and security reviews
- Verify required scans, controls, and approvals before release
- Lead the security escalation path for incidents

### Goals
- Prevent security and compliance issues from reaching production
- Make requirements visible early in planning

### Typical Communication
- Security reviews and release approvals
- Incident communications following the security escalation path

### Interactions with Existing Roles
- **Technical Lead and Developers:** review designs and remediate findings.
- **QA:** align on security testing in the quality gates.
- **Project Managers:** report security risks and approval status.

---

## Release / Operations Lead

### Role Summary
The Release / Operations Lead owns deployment readiness, observability, runbooks, rollback planning, and post-release verification.

### Responsibilities
- Prepare release plans, runbooks, and rollback plans
- Confirm deployment readiness and staging smoke tests
- Monitor releases and verify post-deployment health
- Coordinate release notes and operational handoffs

### Goals
- Deliver safe, predictable releases
- Restore service quickly when issues occur

### Typical Communication
- Release readiness checks and go/no-go updates
- Post-deployment verification reports

### Interactions with Existing Roles
- **Project Managers:** coordinate release milestones and schedules.
- **Developers and QA:** confirm release criteria are met and issues are resolved.
- **Customer / Support Representative:** share release notes and known issues.

---

## Customer / Support Representative

### Role Summary
The Customer / Support Representative brings customer feedback, support trends, and operational impact into prioritization and release planning.

### Responsibilities
- Share customer issues, requests, and support trends
- Provide input on the impact of changes on customers
- Help validate fixes and communicate known issues to customers

### Goals
- Keep planning grounded in real customer needs
- Reduce customer impact from changes and incidents

### Typical Communication
- Regular feedback summaries and support trend reports
- Input during backlog prioritization and release planning

### Interactions with Existing Roles
- **Product Managers:** inform prioritization with customer data.
- **QA and Developers:** report reproducible issues and verify fixes.
- **Release / Operations Lead:** coordinate customer communication around releases.

---

## Change Management / Enablement Lead

### Role Summary
The Change Management / Enablement Lead prepares communications, training, documentation, and adoption support so changes are understood and used.

### Responsibilities
- Plan communications and training for upcoming changes
- Maintain user-facing documentation and guides
- Track adoption and gather feedback after release

### Goals
- Drive smooth adoption of new features and processes
- Reduce confusion and support load after release

### Typical Communication
- Release announcements and training sessions
- Adoption updates shared with stakeholders

### Interactions with Existing Roles
- **Product Managers:** align messaging with product outcomes.
- **Project Managers:** include enablement tasks in plans and timelines.
- **Customer / Support Representative and Release / Operations Lead:** coordinate timing and content of communications.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
