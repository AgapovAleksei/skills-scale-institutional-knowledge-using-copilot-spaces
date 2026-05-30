# OctoAcme Project Management Docs

Welcome! This folder hosts our living documentation for how we manage projects at OctoAcme: from idea to improvement.

## Project Management Process Summary

OctoAcme projects follow a **five-phase lifecycle**: Initiation, Planning, Execution, Release, and Close & Retrospective. We prioritize clear ownership, iterative delivery, regular stakeholder communication, and a culture of continuous learning. Our approach is built on these core principles:

- **Customer-first**: Prioritize customer value and usability in every decision.
- **Iterative delivery**: Deliver small, testable increments to reduce risk and enable feedback.
- **Clear ownership**: Each project has a named Project Manager and Product Manager with defined responsibilities.
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback and learning across all team members.

Every project phase includes checklists and artifacts to ensure consistency and visibility. Responsibilities are clearly documented for all roles—Developers, Product Managers, Project Managers, and Stakeholders—enabling efficient collaboration and reducing friction.

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications.
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success.
- **Developers**: Implement features, collaborate on design, and drive quality.
- **QA/Testing**: Validates acceptance criteria and product quality.
- **Stakeholders**: Provide inputs, context, and approvals.

## Key Workflows & Communication Cadence

- **Daily standups** (15 min): Focus on progress, blockers, and dependencies.
- **Weekly PM + PdM sync**: Strategic alignment and decision-making.
- **Twice-weekly delivery standups**: Team execution and impediment removal.
- **Weekly delivery sync**: Show progress, surface risks, and escalate dependencies.
- **Monthly stakeholder updates**: Transparent reporting using standardized templates.
- **Sprint/milestone demos and reviews**: Regular validation and feedback.

## Quality & Testing Standards

- Unit tests for all new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Small PRs (≤400 lines) with clear acceptance criteria
- At least one approval required before merge

## Process Docs Index

| Document | Purpose |
|----------|---------|
| [**Project Management Overview**](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, principles, roles, and lifecycle. Start here if you're new. |
| [**Project Initiation Guide**](octoacme-project-initiation.md) | Steps to validate a new project idea, align stakeholders, and decide go/no-go for planning. Includes the One-pager template. |
| [**Project Planning**](octoacme-project-planning.md) | How to turn an approved initiative into an actionable plan: backlog creation, estimation, DoD, dependencies, and release planning. |
| [**Execution & Tracking**](octoacme-execution-and-tracking.md) | Day-to-day execution guidance: team rhythm, PR workflow, quality standards, metrics, and blocker escalation. |
| [**Risk Management & Communication**](octoacme-risks-and-communication.md) | Risk identification, assessment, and mitigation. Includes Risk Register template and stakeholder communication best practices. |
| [**Release & Deployment Guide**](octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, rollback procedures, and release notes template. |
| [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) | How to run effective retrospectives, track action items, and build a culture of continuous improvement. |
| [**Roles and Personas**](octoacme-roles-and-personas.md) | Detailed descriptions of Developer, Product Manager, and Project Manager responsibilities, goals, and communication patterns. |

## How to Use These Docs

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md) to understand our approach.

2. **Starting a new project?** Follow this sequence:
   - [Project Initiation Guide](octoacme-project-initiation.md) — validate and align
   - [Project Planning](octoacme-project-planning.md) — create your plan
   - [Execution & Tracking](octoacme-execution-and-tracking.md) — run day-to-day
   - [Risk Management & Communication](octoacme-risks-and-communication.md) — manage risks and stakeholders
   - [Release & Deployment Guide](octoacme-release-and-deployment.md) — ship to production
   - [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — learn and improve

3. **Making process improvements?** Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates.

4. **Keep docs in sync**: Update the relevant process doc whenever you discover a gap, validate a best practice, or incorporate team feedback. These docs live with the code and evolve together.

## Key Artifacts You'll Create

Across the project lifecycle, you'll produce:
- **Project Charter / One-pager** — problem, goal, success metrics, timeline
- **Roadmap and Release Plan** — milestone map and dependency matrix
- **Sprint/Iteration Backlog** — prioritized work with acceptance criteria
- **Risk Register** — identified risks with mitigation plans
- **Status Reports** — weekly updates using standardized templates
- **Retrospective Notes** — learnings and action items

---

**Questions?** Reach out to your Project Manager or Product Manager. These docs are a team resource—help keep them accurate and valuable for everyone.
