# OctoAcme Project Management Processes

Welcome to OctoAcme's project management documentation. This folder centralizes the processes, templates, and guidance used across OctoAcme projects. The goal is to make process artifacts discoverable, consistent, and easy to update so every team member can find the right guidance quickly.

## Overview

OctoAcme runs projects through a lightweight, stage-gated lifecycle that moves from initiation to planning, execution, release, and retrospective. Projects start with a Project One-pager that captures the problem, success metrics, stakeholders, and a high-level timeline; a decision gate ensures success metrics, stakeholder alignment, and team availability before moving into planning. Planning converts approved initiatives into a prioritized, estimable backlog and a release/milestone map.

Workflows emphasize predictable delivery and active risk management. Backlog items include clear acceptance criteria, owners, and estimates; sprints are timeboxed and only pull items that meet the Definition of Done. Execution is tracked on a visible project board (Backlog → Ready → In Progress → In Review → QA → Done) and governed by branching/PR conventions that favor small, reviewable changes. Cross-team dependencies and risks are recorded in a Risk Register and escalated through defined paths from team triage up to sponsor-level when needed.

Roles and communication cadence are explicit. Product Managers define outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement and test code, QA validates acceptance, and stakeholders provide inputs and approvals. The team cadence includes daily standups for progress and blockers, a weekly delivery sync for status and flagged risks, scheduled demos at sprint or milestone ends, and monthly stakeholder updates. A single source of truth (project README or release doc) is recommended for status and incident communications.

Quality assurance and continuous improvement are integral parts of delivery. CI gates run automated tests and security scans before reviews; QA practices include unit tests, integration tests where applicable, end-to-end smoke tests for critical flows, and manual QA when necessary. Pull request rules encourage small PRs with acceptance criteria, CI/lint passing before requesting review, and at least one approval before merge. Retrospectives after sprints, releases, or incidents capture action items that are tracked back into the backlog for continuous improvement.

## Quick start

- New to OctoAcme? Start with [Project Management Overview](octoacme-project-management-overview.md)
- Starting a new initiative? Follow the [Project Initiation Guide](octoacme-project-initiation.md)
- Ready to plan? Use [Project Planning](octoacme-project-planning.md)
- Executing delivery? See [Execution & Tracking](octoacme-execution-and-tracking.md)
- Managing risks or stakeholders? Read [Risk Management & Communication](octoacme-risks-and-communication.md)
- Preparing for deploys? Follow [Release & Deployment Guide](octoacme-release-and-deployment.md)
- Wrapping up? See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- Role definitions: [Personas & Roles](octoacme-roles-and-personas.md)

## Project lifecycle (high level)

1. Initiation — define the problem, stakeholders, success metrics, and produce a one‑pager.
2. Planning — break approved work into shippable backlog items, estimate, and define the Definition of Done.
3. Execution — implement, test, and track work on the project board, and manage risks/dependencies.
4. Release — deploy with quality gates, run smoke tests, and communicate the release.
5. Close & Retrospective — capture learnings, add action items to the backlog, and iterate on processes.

## How to use and contribute

- Use these documents as the single source of truth for process questions. Each doc contains checklists and templates referenced in day-to-day work.
- To propose edits or new content, open an issue using the "Add Content to Project Management Process Docs" template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). That template will guide you to indicate which document to update, a summary, rationale, and suggested text.
- If you want Copilot Spaces to use a doc as context, place process-specific artifacts into `.copilot/` as noted in the Project Management Overview.
- Keep process changes small and assign an owner for each update; link changes to the relevant one-pager, release notes, or risk register where applicable.

## Contact & governance

- The Project Manager (PM) or Product Lead named on a project owns process alignment for that project.
- For doc ownership questions, propose an owner in an issue and tag @wheebs or the relevant project leads.
