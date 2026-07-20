# OctoAcme Project Management Docs

This README is the landing page for OctoAcme's process documentation set. It provides a concise overview of how OctoAcme manages projects and links to all supporting process documents.

## Overview

OctoAcme follows a structured project lifecycle that moves through five stages: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Projects begin with a lightweight one-pager that captures the problem statement, SMART goals, success metrics, and stakeholder alignment. A formal decision gate ensures work only advances to planning when success metrics are clear, stakeholders agree on priority, and team availability is confirmed.

**Core roles** drive accountability throughout the lifecycle. The **Project Manager (PM)** owns delivery coordination, schedules, risk management, and cross-team communications. The **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and validates solutions through data and user research. **Developers** implement features, maintain tests and documentation, and contribute to technical risk identification. **QA** validates acceptance criteria, while **Stakeholders** provide inputs and approvals. Planning activities include a kickoff meeting, backlog creation with acceptance criteria, T-shirt sizing or story point estimation, a Definition of Done, and a formal Risk Register tracking impact, likelihood, owner, and mitigation plans.

**Communication and risk management** are tightly interwoven. The team runs daily standups (15 min), weekly PM–PdM syncs, twice-weekly delivery standups, and monthly stakeholder updates. Escalation follows a clear three-level path — from team-level triage in standup, to PM escalation to Product Lead, up to Sponsor-level escalation for business-impacting issues.

**Execution quality** is maintained through small PRs (≤ 400 lines), CI-enforced automated testing, linting, and security scanning, with at least one required approval before merging. Releases are categorized as Patch, Minor, or Major, each requiring passing CI, merged PRs, drafted release notes, and a documented rollback plan before deploying. After every sprint, release, or incident, a timeboxed **retrospective** captures what went well, what could improve, and 2–3 prioritized action items — ensuring continuous improvement is a first-class practice.

---

## Process Documents

| Document | Description |
|---|---|
| [OctoAcme Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, principles, roles, and lifecycle |
| [OctoAcme Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and create a lightweight plan |
| [OctoAcme Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog, milestones, and release plan |
| [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution guidance: standups, project boards, PR workflows, quality, and metrics |
| [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, stakeholder communication templates, and escalation paths |
| [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook, and release notes template |
| [OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and converting learnings into actionable improvements |
| [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) | Responsibilities and goals for Project Managers, Product Managers, Developers, and QA |
