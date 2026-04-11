# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- QA Engineer: designs test strategies, builds automated/manual test suites, and signs off on quality before release.
- UX Designer: shapes user experience strategy, delivers design assets, and leads usability validation.
- Technical Writer: maintains process and project documentation, drives onboarding, and manages release notes.
- Scrum Master: facilitates ceremonies, removes blockers, and enforces process standards.
- Business Analyst: gathers requirements, maps business processes, and translates stakeholder needs into technical language.
- Stakeholders: provide inputs and approvals.

## Cross-Functional Collaboration Principles
- Every project lifecycle phase has at least one named owner per applicable role.
- Roles collaborate across phase boundaries — handoffs are explicit and documented.
- New team members are onboarded using role-specific guidance from the Roles & Personas document.
- See [ROLE-INTERACTION-MATRIX.md](./ROLE-INTERACTION-MATRIX.md) for a full breakdown of role participation across phases.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed), facilitated by Scrum Master
- Monthly stakeholder updates (with Business Analyst providing requirements status)
- Design review cadence aligned to sprint cycle (UX Designer leads)
- Pre-release quality sign-off from QA Engineer before each deployment
- Documentation handoff from Technical Writer at end of each release cycle
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
