# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured approach to project management focused on customer value, iterative delivery, clear ownership, and data-driven decisions. This documentation centralizes our processes, roles, and artifacts used across all cross-functional projects.

OctoAcme operates on a structured lifecycle that moves projects through five distinct phases: initiation, planning, execution, release, and retrospective. The process begins with validating business needs through a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial timeline. Once approved by leadership, teams move into detailed planning where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a risk register is established. This front-loaded clarity ensures that execution teams have well-defined scope and measurable outcomes before development begins.

Execution is driven by a clear team rhythm that emphasizes transparency and collaboration. Daily standups (15 minutes) surface progress and blockers, while weekly delivery syncs provide opportunities to flag risks and demonstrate progress. The team uses GitHub Projects with a standardized workflow (Backlog → Ready → In Progress → In Review → QA → Done) and enforces quality gates including small PRs (≤400 lines), automated CI/CD with tests and security scanning, and at least one code review approval before merging. End-to-end smoke tests validate critical flows before any release, and metrics around velocity and burndown are tracked consistently.

OctoAcme's core roles—Project Managers, Product Managers, Developers, and QA specialists—have distinct yet complementary responsibilities. Project Managers own delivery coordination, risk management, and stakeholder communication, while Product Managers define outcomes and prioritize the backlog. Developers implement features collaboratively and help identify technical risks, and QA validates quality and acceptance criteria. Communication cascades through weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates, with a clear escalation path (team-level → PM → Product Lead → Sponsor) for blockers and critical issues.

Finally, OctoAcme treats release and learning as equally important. Releases follow a standardized checklist covering pre-release verification, deployment windows, smoke testing, and rollback procedures. Each sprint, release, or milestone concludes with a retrospective (45–75 minutes) to capture what went well and what could improve, converting insights into prioritized action items with clear owners. This cycle of iterative delivery, transparent communication, and continuous improvement enables OctoAcme teams to deliver value predictably while adapting based on evidence and team feedback.

## Core Principles

- **Customer-first:** prioritize customer value and usability
- **Iterative delivery:** deliver small, testable increments
- **Clear ownership:** each project has a named PM and Product Lead
- **Data-informed decisions:** measure impact and iterate
- **Psychological safety:** encourage feedback and learning

## Project Lifecycle

### 1. Initiation

[Project Initiation Guide](octoacme-project-initiation.md) — Define business need, align stakeholders, create one-pager

Validate and authorize work by confirming business need, identifying stakeholders, defining success criteria, and making a go/no-go decision for planning.

### 2. Planning

[Project Planning](octoacme-project-planning.md) — Break work into increments, identify dependencies, create backlog

Turn an approved initiative into an actionable plan by creating a prioritized backlog with acceptance criteria, estimating scope, and identifying dependencies and integration points.

### 3. Execution

- [Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day delivery, quality, testing, metrics
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify risks, escalate blockers, update stakeholders

Manage day-to-day execution through team standups, pull request workflows, quality assurance, and consistent tracking of velocity and metrics. Maintain a risk register and escalate blockers through defined channels while keeping stakeholders informed.

### 4. Release

[Release & Deployment Guide](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback procedures

Standardize how OctoAcme releases features to production by following pre-release requirements, deployment checklists, and rollback procedures to reduce risk and improve observability.

### 5. Close & Improve

[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, convert to action items

Capture learnings after each sprint, release, or milestone by conducting retrospectives and converting insights into prioritized action items with clear owners and timelines.

## Reference

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to roles, artifacts, and communication cadence
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed descriptions of key roles (PM, PdM, Developers, QA)

## Quick Reference: When to Use Each Document

| Phase | Document | Use When |
|-------|----------|----------|
| **Starting a new project** | Project Initiation Guide | You have a new idea or feature proposal ready to explore |
| **Planning delivery** | Project Planning | An initiative is approved and needs detailed planning |
| **Day-to-day work** | Execution & Tracking | You need guidance on team rhythm, PR workflows, and quality gates |
| **Managing risks** | Risk Management & Communication | You need to identify, track, or escalate risks and blockers |
| **Preparing for release** | Release & Deployment Guide | You're ready to move code to production |
| **Learning from delivery** | Retrospective & Continuous Improvement | A sprint or release is complete and you want to capture learnings |
| **Understanding roles** | Roles & Personas | You need clarity on team responsibilities and communication patterns |
| **High-level overview** | Project Management Overview | You're new to OctoAcme and want to understand our approach at a glance |
