# OctoAcme Project Management Overview

OctoAcme runs projects with a customer-first, iterative approach designed to deliver measurable outcomes quickly and safely. Work starts with a lightweight Project One-pager that captures the problem, measurable goals, stakeholders, timeline, and success metrics. Approved initiatives move into planning where teams break the scope into a prioritized backlog using a standardized backlog-item template, estimate work, define a Definition of Done (DoD), and map release milestones. The lifecycle is explicit—Initiation → Planning → Execution → Release → Close/Retro—and core artifacts (one-pager, roadmap, backlog, risk register, acceptance criteria) are kept in-repo as the single source of truth.

Execution uses a board-driven workflow (Backlog, Ready, In Progress, In Review, QA, Done) and a disciplined pull request (PR) process: keep PRs small, link PRs to issues and include acceptance criteria, run CI/lint/security scans before requesting review, and require at least one approval before merging. Teams timebox sprint planning, pull work that meets the DoD and has clear acceptance criteria, and track velocity and burndown. Risks and dependencies are managed in a Risk Register, surfaced on the project board, and escalated during weekly syncs as needed.

Roles are clearly defined so ownership is explicit: Product Managers define outcomes and success metrics, Project Managers coordinate timelines and communications, Developers implement and test, and QA validates acceptance criteria. Communication cadence includes daily standups for blockers and progress, weekly delivery syncs, PM+PdM alignment, sprint-end demos/reviews, and regular stakeholder updates. Quality assurance is integrated into CI and release mechanics: unit/integration tests, end-to-end smoke tests for critical flows, security scanning in CI, manual QA when required, and pre-release checks (passing CI/security scans, release notes, rollback plan, and staging verification).

This docs/ README is a concise entry point — see the other documents in docs/ for detailed templates, checklists, and role descriptions:
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md
