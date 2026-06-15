# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation hub. This collection serves as the centralized reference for how OctoAcme runs projects, manages delivery, and continuously improves workflows.

## Purpose

These documents are designed to:
- Provide a shared understanding of project management processes across OctoAcme
- Enable consistent, repeatable project execution
- Accelerate onboarding and reduce single-person dependency risk
- Empower teams to make decisions aligned with OctoAcme principles
- Capture and evolve institutional knowledge

## OctoAcme Project Management Overview

OctoAcme follows an iterative, customer-first project management approach grounded in clear ownership, data-informed decisions, and psychological safety. The framework is organized into five core phases:

1. **Initiation** — Validate business need, align stakeholders, and confirm measurable outcomes before authorizing work
2. **Planning** — Break initiatives into shippable increments, estimate scope, identify dependencies, and create release timelines
3. **Execution** — Deliver incrementally with a clear team rhythm (standups, syncs, demos), enforce quality gates (testing, CI, security scanning), and manage risks
4. **Release** — Deploy to production using pre-release checklists, smoke tests, and documented rollback plans
5. **Retrospective & Continuous Improvement** — Capture learnings, generate action items, and feed validated improvements back into processes

The organization operates with clearly defined roles—**Project Managers** (coordination and risk management), **Product Managers** (outcomes and prioritization), **Developers** (implementation and quality), and **Stakeholders** (inputs and approvals)—supported by a consistent communication cadence (weekly PM/PdM syncs, twice-weekly standups, monthly stakeholder updates). Execution is managed through backlog-driven workflows, small pull requests with acceptance criteria, and automated CI/CD pipelines. Risk management is embedded throughout via a maintained Risk Register, with escalation paths that move from team-level triage through PM to Product Lead to Sponsor for business-impacting issues.

---

## Documentation Index

| Document | Purpose |
|----------|---------|
| **[Project Management Overview](./octoacme-project-management-overview.md)** | Concise introduction to OctoAcme's approach, roles, principles, artifacts, and lifecycle for new team members |
| **[Project Initiation Guide](./octoacme-project-initiation.md)** | Steps and templates to validate business need, align stakeholders, and authorize new initiatives; includes Project One-pager template and initiation checklist |
| **[Project Planning](./octoacme-project-planning.md)** | Guidance for breaking approved initiatives into actionable backlogs, estimating scope, identifying dependencies, and creating release plans |
| **[Execution & Tracking](./octoacme-execution-and-tracking.md)** | Day-to-day execution guidance including team rhythm (standups, syncs, demos), PR workflows, quality standards, blocker escalation, and metrics tracking |
| **[Risks & Communication](./octoacme-risks-and-communication.md)** | How to identify, manage, and communicate risks; maintain risk registers; escalate dependencies; and provide stakeholder updates |
| **[Release & Deployment](./octoacme-release-and-deployment.md)** | Standardized release process including pre-release requirements, deployment checklists, rollback playbooks, and release notes templates |
| **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** | How to run retrospectives after sprints or milestones, track action items, and measure impact of improvements |
| **[Roles & Personas](./octoacme-roles-and-personas.md)** | Detailed descriptions of typical project roles (Developers, Product Managers, Project Managers) with responsibilities, goals, and communication patterns |

---

## How to Propose Updates

The OctoAcme process documents are living artifacts that evolve with team feedback and lessons learned. To propose updates, additions, or new process documents:

1. Use the **[Process Doc Update issue template](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** to create an issue
2. Describe the gap, improvement, or new content you'd like to add
3. Include rationale and suggested content if available
4. The team will review, refine, and integrate validated improvements

---

## Quick Links

- **Getting Started:** Start with [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction
- **Starting a New Project:** Follow [Project Initiation Guide](./octoacme-project-initiation.md) → [Project Planning](./octoacme-project-planning.md)
- **Day-to-Day Delivery:** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risks & Communication](./octoacme-risks-and-communication.md)
- **Preparing to Release:** Use [Release & Deployment](./octoacme-release-and-deployment.md) pre-release checklist
- **Learning & Improving:** Schedule a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

## Using These Docs in Copilot Spaces

These process documents are designed to be used as context in Copilot Spaces to provide role-specific, process-informed guidance. You can reference specific documents and sections when setting up a Space for:
- Project kickoff and planning
- Delivery team coordination
- Risk management and escalation
- Release planning and execution
- Post-project retrospectives and continuous improvement

For more information on Copilot Spaces, see the [main repository README](../README.md).
