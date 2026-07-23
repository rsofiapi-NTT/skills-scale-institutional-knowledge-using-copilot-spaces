# OctoAcme Project Management Docs

This README is the entry point for OctoAcme's project management documentation. Use it to orient yourself to how OctoAcme teams plan, execute, and deliver work, and to navigate to the detailed process guides below.

## Overview

OctoAcme's project management approach is structured around a clear lifecycle with lightweight but consistent governance: initiation, planning, execution, release, and retrospective improvement. Work begins with a one-pager that defines the problem, SMART goal, success metrics, stakeholders, early risks, and resource needs. A decision gate ensures projects only move forward when outcomes are measurable, stakeholder priority is aligned, and team capacity is confirmed. From there, planning translates approved initiatives into prioritized backlog items with acceptance criteria, estimates, dependencies, milestones, and a documented Definition of Done.

Execution is managed through a disciplined team rhythm and transparent workflow tracking. Teams use project boards with staged columns (Backlog → Ready → In Progress → In Review → QA → Done), keep pull requests small where possible, and include issue links plus acceptance criteria in PR descriptions. Daily standups and weekly delivery syncs keep progress, blockers, and dependencies visible, while sprint-end demos and reviews reinforce iterative delivery. Risk escalation is explicit and tiered: team triage first, then PM-led escalation to product and dependent teams, and finally sponsor-level escalation for business-critical issues.

Roles are intentionally differentiated to balance delivery speed and decision quality. Product Managers own problem framing, prioritization, and outcome measurement; Project Managers coordinate plans, timelines, risks, and cross-team communication; Developers implement, test, and surface technical risks; QA/Testing validates acceptance and release readiness; and Stakeholders provide direction and approvals. This role clarity supports strong ownership while maintaining cross-functional alignment through shared artifacts such as roadmaps, risk registers, acceptance criteria, and retrospective action logs.

Communication and quality are treated as core operating mechanisms rather than afterthoughts. Cadences include PM/PdM weekly alignment, recurring delivery standups, stakeholder updates, and structured escalation and incident communications when needed. Quality assurance spans unit testing for new logic, integration testing where relevant, end-to-end smoke tests for critical flows, CI lint/test gates, and security scanning before release. Release readiness also requires documented rollback planning, post-deploy verification, and stakeholder announcements, while retrospectives convert lessons learned into tracked, owner-assigned improvements for continuous process refinement.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level summary of OctoAcme's end-to-end project management lifecycle and guiding principles. |
| [Project Initiation](octoacme-project-initiation.md) | Covers the one-pager template, stakeholder identification, success metrics, and the project decision gate. |
| [Project Planning](octoacme-project-planning.md) | Describes backlog creation, acceptance criteria, estimation, dependency mapping, milestones, and Definition of Done. |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Details the project board workflow, PR hygiene practices, daily/weekly team rhythms, and escalation levels. |
| [Risks and Communication](octoacme-risks-and-communication.md) | Explains the risk register process, communication cadences, status updates, and incident communication guidelines. |
| [Release and Deployment](octoacme-release-and-deployment.md) | Outlines release readiness criteria, rollback planning, deployment steps, and post-deploy verification. |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Guides teams through sprint retrospectives, action item tracking, and feeding improvements back into process. |
| [Roles and Personas](octoacme-roles-and-personas.md) | Defines responsibilities and ownership for Product Manager, Project Manager, Developers, QA/Testing, and Stakeholders. |

## Using These Docs in Copilot Spaces and Onboarding

**Copilot Spaces:** Add the `docs/` folder (or individual documents) as context sources in your Copilot Space so that GitHub Copilot can answer questions about OctoAcme's processes inline. Prioritize `octoacme-project-management-overview.md` and `octoacme-roles-and-personas.md` as anchors, then add the specific lifecycle documents relevant to your team's current phase.

**Onboarding:** New team members should start with this README to get the big picture, then read the [Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md) documents before diving into the phase-specific guides that match their role. Use these docs as living references throughout delivery—they are designed to answer "how do we do this here?" at every stage of a project.
