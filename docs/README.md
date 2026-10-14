# OctoAcme Project Management Docs

This folder contains the project management processes used by OctoAcme, from project initiation to continuous improvement.

## Overview

OctoAcme uses a structured project lifecycle that moves work through initiation, planning, execution, release, and retrospectives. Projects begin by defining the problem, SMART goal, success metrics, stakeholders, timeline, risks, and resource needs in a project one-pager. Once stakeholders approve the initiative, the team creates a prioritized backlog, estimates work, identifies dependencies, defines the Definition of Done, and establishes release milestones.

Execution is managed through a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done. Teams work in small, shippable increments supported by focused pull requests, clear acceptance criteria, issue links, and required reviews. Project Managers coordinate schedules, risks, dependencies, meetings, and status reporting; Product Managers define outcomes, prioritize the backlog, and measure product impact; Developers implement and test solutions; QA validates acceptance criteria and overall quality; and stakeholders provide feedback, decisions, and approvals.

Communication relies on a consistent rhythm and a shared source of truth. Delivery teams use daily or twice-weekly standups to discuss progress, blockers, and dependencies, while PMs and Product Managers align weekly and provide regular stakeholder updates. Risks are recorded in a risk register with impact, likelihood, owners, mitigation plans, and status, then reviewed during weekly syncs. Blockers escalate from the team to the Project Manager, Product Lead, and sponsor when they threaten delivery or business outcomes; security incidents follow a dedicated security escalation path.

Quality assurance is integrated throughout delivery rather than reserved for the end. New logic should include unit tests, with integration tests and end-to-end smoke tests added where appropriate. Continuous integration runs automated tests, linting, and security scans before review, while manual QA confirms feature acceptance when needed. Before release, all acceptance criteria must be met, CI and security checks must pass, release notes and rollback plans must be prepared, and staging smoke tests and post-deployment verification must be completed. After each sprint, release, milestone, or incident, retrospectives capture what went well, what needs improvement, and a small set of owned action items for continuous improvement.

## Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
