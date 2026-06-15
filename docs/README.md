# OctoAcme Project Management Docs

## Purpose

This collection of documents standardizes how OctoAcme runs projects, from initiation through delivery and continuous improvement. These guides help teams align on processes, roles, and decision-making frameworks—enabling consistent, repeatable project execution across the organization.

New team members should start here to understand OctoAcme's approach. For specific questions or to propose updates, refer to the [How to Propose Updates](#how-to-propose-updates) section.

---

## Quick Summary of OctoAcme Processes

OctoAcme follows a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decision-making. The organization operates projects through five distinct lifecycle phases:

1. **Initiation**: Validate business needs and create a lightweight Project One-pager that defines the problem statement, success metrics, stakeholders, and high-level timeline. Once approved, move to planning.

2. **Planning**: Break work into shippable increments with prioritized backlogs, acceptance criteria, and a clear Definition of Done. Identify dependencies, risks, and integration points to ensure alignment before execution begins.

3. **Execution**: Maintain a consistent team rhythm through daily standups, weekly delivery syncs, and sprint-based planning. Use GitHub Projects for workflow visibility, enforce small reviewable pull requests (≤400 lines), and embed quality through CI/CD automation, testing, and code reviews.

4. **Release**: Conduct pre-release verification (acceptance criteria met, CI passing, release notes drafted) and deploy using standardized checklists. Document rollback plans and post-deploy verifications to minimize production risk.

5. **Close & Retrospective**: Hold retrospectives after each sprint, release, or milestone to capture learnings and convert them into actionable improvements with clear owners and due dates.

Across all phases, OctoAcme maintains continuous risk management, stakeholder communication, and a "psychological safety" culture that encourages feedback and learning. Clear roles—**Project Managers** coordinate delivery and timelines, **Product Managers** define outcomes and prioritize the backlog, **Developers** implement features and collaborate on quality, and **Stakeholders** provide inputs and approvals—ensure accountability and alignment.

---

## Process Documents

### Core Overview
- **[Project Management Overview](./octoacme-project-management-overview.md)**  
  A concise introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle. Start here for a bird's-eye view of how the organization runs projects.

### Lifecycle Phases

- **[Project Initiation Guide](./octoacme-project-initiation.md)**  
  Steps and templates to validate and authorize new initiatives. Includes a Project One-pager template, stakeholder alignment checklist, and decision gate criteria.

- **[Project Planning](./octoacme-project-planning.md)**  
  Guidance for turning an approved initiative into an actionable backlog and delivery plan. Covers kickoff, backlog estimation, Definition of Done, and risk/dependency identification.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)**  
  Guidance for managing day-to-day execution and tracking progress toward milestones. Describes team rhythm (standups, syncs, demos), PR workflows, quality practices, and blocker escalation.

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)**  
  Standardized approach to releasing features and deploying to production. Includes pre-release requirements, deployment checklist, rollback/incident playbook, and release notes template.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)**  
  Framework for capturing learnings and converting them into actionable improvements. Covers retrospective structure, action item tracking, and continuous improvement culture.

### Cross-Cutting Guidance

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)**  
  Explains how to identify, manage, and communicate risks and dependencies. Includes Risk Register template, stakeholder communication templates, and escalation paths.

- **[Roles & Personas](./octoacme-roles-and-personas.md)**  
  Defines typical roles (Developers, Product Managers, Project Managers) and responsibilities used across OctoAcme project docs. Use these personas to frame scenarios and understand role-specific responsibilities.

---

## How to Propose Updates

To add content or suggest improvements to these process documents:

1. Open a new issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template.
2. Select the document you want to update (or note if it's a new document).
3. Describe the new content, why it's needed, and provide suggested text if available.
4. A team member will review your proposal and merge it into the documentation.

This ensures all process updates are reviewed, tracked, and made visible to the team.

---

## Key Artifacts Across Projects

- **Project Charter / One-pager**: Problem statement, goal, success metrics, stakeholders, timeline
- **Roadmap and Release Plan**: High-level feature sequencing and release dates
- **Sprint/Iteration Backlog**: Prioritized, estimated work with acceptance criteria
- **Risk Register**: Active risks, likelihood, impact, and mitigation plans
- **Retrospective Notes**: Learnings, action items, and follow-ups

---

## Communication Cadence

- **Daily**: Team standups (15 minutes)
- **Weekly**: PM + PdM sync, delivery team standups, risk review
- **Bi-weekly/Sprint-based**: Sprint planning and demos
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communication

---

## Questions?

If you have questions about these processes or need clarification, reach out to your Project Manager or Product Manager. For suggestions on how to improve these docs, see [How to Propose Updates](#how-to-propose-updates).
