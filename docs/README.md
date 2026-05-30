# OctoAcme Project Management Processes

## Overview

This folder contains comprehensive documentation of the OctoAcme project management framework and processes. OctoAcme is designed to help teams deliver product features, services, and integrations through structured, customer-first practices that emphasize iterative delivery, clear ownership, and continuous improvement.

## Project Management Process Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes stakeholder alignment, iterative delivery, and data-informed decision-making. The framework is built on five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need and create a lightweight Project One-pager that defines the problem statement, success metrics, stakeholders, and initial timeline. Once approved, the Planning phase breaks work into shippable increments with clear acceptance criteria, estimates, and a defined Definition of Done. This structured approach ensures teams move into execution with clarity and stakeholder buy-in, reducing rework and scope creep.

Execution and delivery are coordinated through a regular team rhythm that includes daily standups (15 minutes), weekly delivery syncs, and end-of-sprint demos. The team uses GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain visibility, while Pull Requests are kept small (≤400 lines) and require at least one approval before merging. Quality is embedded throughout this phase via unit tests, integration tests, and end-to-end smoke tests before release, supplemented by security scanning in CI and manual QA when needed. Risk and dependency management is continuous—teams maintain a Risk Register and escalate blockers through three levels: team triage, PM escalation to Product Lead, and sponsor-level escalation for business-critical issues.

OctoAcme defines clear roles and responsibilities across the delivery organization. **Project Managers (PMs)** coordinate schedules, manage risks, and facilitate communication; **Product Managers (PdMs)** define outcomes, prioritize the backlog, and measure success; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates acceptance criteria and quality. Communication happens through multiple channels—weekly PM-PdM syncs, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations—with a single source of truth (project README or release documents) for status. This multi-role structure ensures accountability while fostering psychological safety and customer-first decision-making.

Finally, OctoAcme emphasizes continuous improvement and learning. Release and Deployment processes are standardized with pre-release checklists, rollback plans, and post-deployment verification to reduce risk. Retrospectives are held after each sprint or milestone to capture what went well, what could improve, and to assign concrete action items with owners and due dates. This cycle of delivery, measurement, reflection, and iterative improvement—grounded in core principles of customer value, clear ownership, and psychological safety—enables OctoAcme teams to scale delivery while maintaining quality and organizational learning.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Documentation Structure

- **[octoacme-project-management-overview.md](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[octoacme-project-initiation.md](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[octoacme-project-planning.md](octoacme-project-planning.md)** — Breaking an approved initiative into an actionable plan and backlog
- **[octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)** — Managing day-to-day execution and tracking progress toward milestones
- **[octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)** — Identifying, managing, and communicating risks and dependencies
- **[octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)** — Standardizing release and deployment processes to reduce risk
- **[octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and converting them into actionable improvements
- **[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)** — Defining typical roles, responsibilities, and personas used in OctoAcme projects

## Getting Started

**New to OctoAcme?** Start with [octoacme-project-management-overview.md](octoacme-project-management-overview.md) for a concise introduction.

**Starting a new project?** Follow the phases in order:
1. [Initiation](octoacme-project-initiation.md)
2. [Planning](octoacme-project-planning.md)
3. [Execution](octoacme-execution-and-tracking.md)
4. [Release](octoacme-release-and-deployment.md)
5. [Close & Retrospective](octoacme-retrospective-and-continuous-improvement.md)

**Managing risks or communicating status?** See [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md).

**Understanding roles and responsibilities?** See [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).

## Contributing to These Docs

To propose updates, additions, or clarifications to the OctoAcme process documentation, please create an issue using the [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.

All process improvements should be reviewed with stakeholders and aligned with the OctoAcme principles before being incorporated.
