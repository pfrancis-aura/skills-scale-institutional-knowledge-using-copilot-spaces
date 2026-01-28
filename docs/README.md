# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation. This README provides a concise entry point to all project management resources, playbooks, and templates for the OctoAcme organization.

## Project Management Process Overview

OctoAcme uses a consistent, customer-first project management lifecycle to ensure clarity, accountability, and iterative delivery across all cross-functional projects. The process is grounded in several core principles: prioritizing customer value, delivering small testable increments, maintaining clear ownership with named Project Managers and Product Leads, making data-informed decisions, and fostering psychological safety for feedback and learning.

The project lifecycle follows five key phases: **Initiation** validates ideas and creates a project one-pager with stakeholders, goals, and success metrics; **Planning** breaks work into prioritized backlog items with acceptance criteria, estimates, and a release plan; **Execution** manages day-to-day delivery through standups, PR workflows, automated testing, and quality gates; **Release** standardizes deployments with pre-release checklists, smoke tests, and rollback plans; and **Retrospective** captures learnings and converts them into actionable improvements. Throughout these phases, teams follow defined communication cadences including weekly PM-PdM syncs, twice-weekly standups, and monthly stakeholder updates, with clear escalation paths for blockers.

Quality assurance is embedded throughout the delivery process. All code changes follow a PR workflow with automated CI testing and linting, requiring at least one approval before merging. Teams maintain unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows. Security scanning runs in CI pipelines, and manual QA validates feature acceptance when needed. The Definition of Done and acceptance criteria ensure consistent quality standards, while the risk register tracks and mitigates potential issues proactively.

Key roles include the **Project Manager** (coordinates delivery, schedules, risks, and communications), **Product Manager** (defines outcomes, prioritizes backlog, and measures success), **Developers** (implement features and maintain code quality), **QA/Testing** (validate quality and acceptance criteria), and **Stakeholders** (provide inputs and approvals). Together, these roles collaborate using standardized artifacts such as project charters, roadmaps, sprint backlogs, risk registers, and retrospective notes to deliver value repeatably and transparently.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) - High-level principles, roles, and lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) - Validate ideas, align stakeholders, create one-pager
- [Project Planning](octoacme-project-planning.md) - Break down scope, estimate work, define release plan
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day delivery, PR workflows, quality gates
- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Standardized deployment process and rollback plans
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and action items
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Risk register, stakeholder updates, escalation paths
- [Roles & Personas](octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities

## Getting Started

New to OctoAcme project management? Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and approach. Then review the [Roles & Personas](octoacme-roles-and-personas.md) guide to understand your responsibilities. When starting a new project, follow the process documents in order from Initiation through Retrospective.

## Using These Docs

- Keep your Project Charter updated in your project repository
- Add process-specific documentation to `.copilot/` if you want Copilot Spaces to use them as context
- Reference these docs in your team onboarding materials
- Contribute improvements through pull requests to keep our practices current
