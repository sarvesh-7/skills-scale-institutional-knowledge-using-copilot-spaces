# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This README provides a high-level overview of how OctoAcme runs projects and links to all available process documents so new and returning team members can quickly find what they need.

---

## Overview

OctoAcme follows a structured, iterative project lifecycle guided by a set of core principles: customer-first decision-making, iterative delivery of small testable increments, clear ownership with named Project and Product Managers, data-informed prioritization, and a culture of psychological safety that encourages learning and feedback. Every cross-functional project that delivers product features, services, or integrations uses the processes described in these docs.

## Project Lifecycle

OctoAcme projects move through five phases:

1. **Initiation** — Validate the business need, identify stakeholders, define success metrics, and produce a lightweight Project One-pager. A decision gate (go/no-go) is held before planning begins.
2. **Planning** — Break approved work into shippable increments with acceptance criteria, estimate scope, create a release plan, and document risks and dependencies.
3. **Execution** — Manage day-to-day delivery using GitHub Projects boards (Backlog → Ready → In Progress → In Review → QA → Done). Teams hold twice-weekly standups and weekly delivery syncs. Pull requests are kept small (≤ 400 lines) and require at least one approval plus passing CI before merging.
4. **Release** — Follow a pre-release checklist (all acceptance criteria met, passing CI and security scans, rollback plan documented) and a deployment checklist covering staging smoke tests, production deploy, post-deploy verification, and stakeholder announcement.
5. **Close & Retrospective** — Conduct a blameless retrospective (45–75 min) to capture what went well and identify 2–3 prioritized action items that feed back into the team backlog for continuous improvement.

## Key Roles & Responsibilities

| Role | Summary |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, and communications to ensure on-time, in-scope delivery. |
| **Product Manager (PdM)** | Defines what should be built, prioritizes the roadmap and backlog, and measures outcomes against success metrics. |
| **Developers** | Design, build, test, and document features to meet acceptance criteria; participate in design and code reviews. |
| **QA Engineer** | Designs test strategies, builds automated/manual test suites, triages defects, and signs off on quality before release. |
| **UX Designer** | Shapes user experience strategy, delivers wireframes and design assets, and leads usability validation. |
| **Technical Writer** | Maintains process and project documentation, drives onboarding clarity, and manages release notes. |
| **Scrum Master** | Facilitates agile ceremonies, removes blockers, and enforces process standards. |
| **Business Analyst** | Gathers and documents requirements, maps business processes, and translates stakeholder needs into technical language. |
| **Stakeholders** | Provide inputs, approvals, and milestone-based status updates. |

Each project has a named PM and PdM, creating clear accountability and reducing single-person dependency. See the [Role Interaction Matrix](./ROLE-INTERACTION-MATRIX.md) for a breakdown of cross-functional collaboration across the project lifecycle.

## Communication Strategies & Cadences

| Cadence | Audience | Purpose |
|---|---|---|
| Twice-weekly standups | Delivery team | Surface blockers, dependencies, and daily progress |
| Weekly PM + PdM sync | PM, PdM | Alignment on scope, risks, and backlog priorities |
| Weekly delivery sync | Full team | Demonstrate progress, review flagged risks |
| Monthly stakeholder updates | Stakeholders | Provide status, upcoming milestones, and decisions needed |
| Ad-hoc escalations | As needed | Resolve blockers at Team → PM → Product Lead → Sponsor levels |

Status updates use a standard template covering progress, next steps, risks & blockers, and decisions needed.

## Quality Assurance Practices

Quality is built in throughout the project lifecycle:

- **Unit tests** for all new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical user flows before release
- **Security scanning** in every CI pipeline
- **Manual QA** for feature acceptance when automation is insufficient
- **PR policy**: at least one approval required; all automated tests and linting must pass before merging
- **Post-release monitoring**: velocity, burndown, error rates, latency, and usage metrics tracked against success metrics defined in the Project One-pager

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, principles, roles, artifacts, and communication cadence |
| [Project Initiation](./octoacme-project-initiation.md) | Steps to validate and authorize new work, including the Project One-pager template and initiation checklist |
| [Project Planning](./octoacme-project-planning.md) | How to build an actionable backlog, estimate scope, define the Definition of Done, and create a release plan |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day team rhythm, GitHub Projects workflow, PR conventions, quality and testing expectations, and escalation paths |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register format, risk lifecycle, stakeholder communication templates, and escalation paths |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Pre-release requirements, deployment checklist, rollback playbook, and release notes template |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, facilitation guidance, action item tracking, and continuous improvement culture |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and typical communication patterns for each role (Developers, PdMs, PMs, QA Engineers, UX Designers, Technical Writers, Scrum Masters, Business Analysts) |
| [Role Interaction Matrix](./ROLE-INTERACTION-MATRIX.md) | Cross-functional role participation by lifecycle phase, key interaction points, communication frequency, and responsibility ownership |
