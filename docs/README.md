# OctoAcme Project Management Process Documentation

## Overview

This directory contains comprehensive documentation of the OctoAcme project management framework. The materials are designed to centralize scattered project management knowledge, convert tacit team insights into searchable, versioned artifacts, and give all team members equal access to processes, decisions, and rationale.

## OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes stakeholder alignment, iterative delivery, and data-informed decision-making. The framework is built on five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need and create a lightweight Project One-pager that defines the problem statement, success metrics, stakeholders, and initial timeline. Once approved, the Planning phase breaks work into shippable increments with clear acceptance criteria, estimates, and a defined Definition of Done. This structured approach ensures teams move into execution with clarity and stakeholder buy-in, reducing rework and scope creep.

Execution and delivery are coordinated through a regular team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and end-of-sprint demos. The team uses GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain visibility, while Pull Requests are kept small (≤400 lines) and require at least one approval before merging. Quality is embedded throughout this phase via unit tests, integration tests, and end-to-end smoke tests before release, supplemented by security scanning in CI and manual QA when needed. Risk and dependency management is continuous—teams maintain a Risk Register and escalate blockers through three levels: team triage, PM escalation to Product Lead, and sponsor-level escalation for business-critical issues.

OctoAcme defines clear roles and responsibilities across the delivery organization. **Project Managers (PMs)** coordinate schedules, manage risks, and facilitate communication; **Product Managers (PdMs)** define outcomes, prioritize the backlog, and measure success; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates acceptance criteria and quality. Communication happens through multiple channels—weekly PM-PdM syncs, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations—with a single source of truth (project README or release documents) for status. This multi-role structure ensures accountability while fostering psychological safety and customer-first decision-making.

Finally, OctoAcme emphasizes continuous improvement and learning. Release and Deployment processes are standardized with pre-release checklists, rollback plans, and post-deployment verification to reduce risk. Retrospectives are held after each sprint or milestone to capture what went well, what could improve, and to assign concrete action items with owners and due dates. This cycle of delivery, measurement, reflection, and iterative improvement—grounded in core principles of customer value, clear ownership, and psychological safety—enables OctoAcme teams to scale delivery while maintaining quality and organizational learning.

## Key Documents

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme principles, core roles, key artifacts, and the project lifecycle
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones
- **[Risks & Communication](./octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized processes for releasing features to production
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of typical roles and responsibilities in OctoAcme projects

## Purpose

These process documents serve to:

- Centralize scattered project management knowledge in one accessible location
- Convert tacit team insights into searchable, versioned artifacts
- Give all team members equal access to processes, decisions, and rationale
- Connect repository documentation as a structured knowledge source
- Extract, refine, and standardize workflows collaboratively
- Feed validated improvements back into living documentation
- Accelerate onboarding and reduce single-person dependency risk
- Enable consistent, repeatable project execution

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Reference the relevant process guide based on your project phase (initiation, planning, execution, etc.)
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Update process documents using the issue template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`

## Contributing

To propose updates or additions to these process documents, use the **"Add Content to Project Management Process Docs"** issue template in `.github/ISSUE_TEMPLATE/`. This ensures proposed changes are reviewed and aligned with the team's project management approach.
