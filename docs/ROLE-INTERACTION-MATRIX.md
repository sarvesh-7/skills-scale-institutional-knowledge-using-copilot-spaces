# OctoAcme Role Interaction Matrix

This document shows which roles participate in each phase of the project lifecycle, key interaction points between personas, and ownership of critical activities. Use this as a quick reference when onboarding, planning, or resolving accountability questions.

---

## Phase Participation by Role

| Phase | PM | PdM | Developers | QA Engineer | UX Designer | Technical Writer | Scrum Master | Business Analyst | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Initiation | ✅ | ✅ | ⬜ | ⬜ | ⬜ | ⬜ | ⬜ | ✅ | ✅ |
| Planning | ✅ | ✅ | ✅ | ✅ | ✅ | ⬜ | ✅ | ✅ | ✅ |
| Execution | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⬜ |
| Release | ✅ | ✅ | ✅ | ✅ | ⬜ | ✅ | ✅ | ✅ | ✅ |
| Retrospective | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⬜ |

> ✅ = Active participant | ⬜ = Not typically involved

---

## Key Interaction Points Between Roles

### Project Manager ↔ All Roles
- Coordinates delivery schedules, tracks milestones, and escalates risks
- Primary communication hub for status updates and stakeholder reporting

### Product Manager ↔ Business Analyst
- Collaborate on requirements elicitation, backlog refinement, and feature prioritization
- Business Analyst translates stakeholder input into stories; PdM sets priority

### Product Manager ↔ UX Designer
- Align on user experience goals and success metrics for features
- UX Designer brings usability evidence back to inform product decisions

### Developers ↔ QA Engineer
- Developers deliver testable builds; QA Engineer validates against acceptance criteria
- Pair on defect triage and resolution; QA signs off before features are marked done

### Developers ↔ UX Designer
- UX Designer provides specs and answers implementation questions
- Developers raise feasibility concerns early; UX adjusts designs accordingly

### Developers ↔ Technical Writer
- Technical Writer captures implementation details and API changes for documentation
- Developers review technical content for accuracy before publication

### QA Engineer ↔ Product Manager
- QA reviews acceptance criteria for testability; flags ambiguities before development
- PdM confirms feature readiness for release based on QA sign-off

### Scrum Master ↔ Project Manager
- Scrum Master surfaces delivery impediments and team health signals
- Project Manager escalates blockers that require cross-team or stakeholder intervention

### Scrum Master ↔ All Roles
- Facilitates all sprint ceremonies (planning, standup, review, retrospective)
- Coaches team members in agile practices and continuous improvement

### Business Analyst ↔ Stakeholders
- Elicits and documents requirements through workshops and interviews
- Validates that delivered features meet the original business intent

### Technical Writer ↔ All Roles
- Collaborates with subject matter experts to produce accurate documentation
- Owns release notes and ensures documentation is ready before each release

---

## Communication Frequency Summary

| Interaction | Frequency |
|---|---|
| PM + PdM alignment | Weekly |
| Daily standup (full team) | Daily (facilitated by Scrum Master) |
| Design review (UX + Developers + PdM) | Each sprint |
| QA status update (QA Engineer + PM + Developers) | Daily standup + ad hoc |
| Requirements review (Business Analyst + PdM + Stakeholders) | Per planning cycle |
| Documentation handoff (Technical Writer + Developers/PdM) | End of each release cycle |
| Stakeholder status update (PM + Business Analyst) | Monthly (or milestone-based) |
| Retrospective (all team roles) | End of each sprint |

---

## Responsibility Ownership for Critical Activities

| Activity | Primary Owner | Supporting Roles |
|---|---|---|
| Requirements definition | Business Analyst | Product Manager, Stakeholders |
| Backlog prioritization | Product Manager | Business Analyst, Project Manager |
| UX design and prototyping | UX Designer | Product Manager, Developers |
| Sprint facilitation | Scrum Master | Project Manager |
| Feature implementation | Developers | UX Designer, QA Engineer |
| Test strategy and execution | QA Engineer | Developers |
| Defect triage | QA Engineer | Developers, Product Manager |
| Release quality sign-off | QA Engineer | Project Manager |
| Post-deployment validation | Business Analyst | QA Engineer, Product Manager |
| Release notes and communication | Technical Writer | Product Manager, Developers |
| Process documentation | Technical Writer | All roles (as subject matter experts) |
| Risk register maintenance | Project Manager | Scrum Master, All roles |
| Retrospective facilitation | Scrum Master | Project Manager |

---

## References
- [Roles & Personas](./octoacme-roles-and-personas.md) — Full role descriptions, responsibilities, and goals
- [Project Management Overview](./octoacme-project-management-overview.md) — Core principles and communication cadence
- [Project Planning](./octoacme-project-planning.md) — Planning activities and role involvement
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day team rhythm and quality standards
- [Release & Deployment](./octoacme-release-and-deployment.md) — Release process and role sign-offs
