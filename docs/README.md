# OctoAcme Project Management Docs

This folder contains all process documentation for how OctoAcme plans, executes, and delivers cross-functional projects. Use this README as your entry point to quickly orient yourself and navigate to the relevant guides.

## Project Management Process Overview

OctoAcme runs projects through a lightweight, repeatable lifecycle: **Initiation → Planning → Execution → Release → Retrospective/Continuous Improvement**. In **Initiation**, the team validates the business need and defines measurable outcomes using a Project One-pager (problem, SMART goal, success metrics), a stakeholder list and communication plan, a high-level timeline with milestones, initial risks, and resourcing needs. A decision gate confirms readiness to move forward: metrics and priority are clear, stakeholders are aligned, and team capacity is confirmed.

In **Planning**, the approved initiative is broken into shippable increments with acceptance criteria, sized using lightweight estimation (e.g., T-shirt sizing or story points), and governed by a documented Definition of Done. Dependencies and integration points are explicitly identified and tracked, and risks are captured in a simple risk register (impact, likelihood, owner, mitigation, status), with cross-team dependencies highlighted on the project board and escalated as needed, alongside a release plan covering scope, rollout, rollback strategy, and release notes.

During **Execution & Tracking**, delivery is supported by a consistent team rhythm: daily standups for progress and blockers, weekly delivery syncs to surface risks, and end-of-sprint or milestone demos. Work flows across a board (e.g., Backlog → Ready → In Progress → In Review → QA → Done), with the PR process emphasizing small reviewable changes, linked issues, CI checks (tests, lint, security scanning), and required approvals before merge. Blockers follow a defined escalation path from team triage to PM-led escalation to sponsor-level escalation for business-impacting issues.

**Roles and communication** are intentionally explicit. Core personas include the **Project Manager** (coordination, schedule, risk, comms), **Product Manager/Product Lead** (outcomes, prioritization, success measurement), **Developers** (implementation, reviews, tests, technical risk mitigation), **QA/Testing** (acceptance validation), and **Stakeholders** (inputs and approvals). Stakeholder communication uses a single source of truth (the project README or release doc) with regular weekly or milestone-based status updates and templates for incident comms. Releases follow a standardized checklist — acceptance criteria met, CI and security scans passing, release notes and rollback plan ready, staging smoke tests done, post-deploy verification complete, and an announcement sent — and the loop is closed through structured retrospectives that produce owned action items reviewed in ongoing PM syncs.

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, principles, roles, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | One-pager template, stakeholder alignment, and decision gate for starting a project |
| [Project Planning Guide](octoacme-project-planning.md) | Backlog creation, estimation, Definition of Done, dependencies, risks, and release planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Team rhythm, board workflow, PR process, metrics, and escalation paths |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, weekly/milestone updates, incident comms, and escalation |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, staging/prod deployment, verification, announcements, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action items, and tracking improvements over time |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities for PM, PdM, Developers, QA, and Stakeholders |

---

> Use these docs to quickly access process guides, learn OctoAcme's PM approach, and contribute improvements. For project-specific context to use with Copilot Spaces, add relevant process docs to your `.copilot/` folder.
