# OctoAcme — Role Handoff Checklist

## Purpose
Clarify ownership and handoffs across roles at each major phase of a project, reducing gaps and ensuring nothing falls through the cracks.

---

## Initiation → Planning Handoff

| # | Handoff Item | Owner | Receiver |
|---|---|---|---|
| 1 | Problem statement and SMART goals confirmed | Product Manager | Project Manager, Scrum Master |
| 2 | Initial success metrics and KPIs defined | Product Manager, Data Analyst | Project Manager |
| 3 | Stakeholder list and communication plan drafted | Project Manager | All roles |
| 4 | Design research needs identified | Product Manager | UI/UX Designer |
| 5 | Data instrumentation requirements flagged | Data Analyst | Developers |

**Checklist:**
- [ ] Project One-pager reviewed and approved
- [ ] Success metrics agreed and logged in project tracker
- [ ] UI/UX discovery tasks added to the backlog
- [ ] Data Analyst briefed on product goals

---

## Planning → Execution Handoff

| # | Handoff Item | Owner | Receiver |
|---|---|---|---|
| 1 | Prioritized backlog with acceptance criteria | Product Manager | Developers, Scrum Master |
| 2 | Design specifications and prototypes for sprint items | UI/UX Designer | Developers |
| 3 | Release timeline and milestones documented | Project Manager, Release Manager | All roles |
| 4 | Definition of Done reviewed and agreed | Scrum Master | Developers, QA |
| 5 | Risk register seeded with known risks | Project Manager | All roles |

**Checklist:**
- [ ] Backlog refined and sprint-ready stories confirmed
- [ ] Designs approved and accessible to Developers
- [ ] Release dates communicated to Release Manager
- [ ] Definition of Done documented and visible to the team

---

## Execution → QA Handoff

| # | Handoff Item | Owner | Receiver |
|---|---|---|---|
| 1 | Feature branches merged with passing CI | Developers | QA / Release Manager |
| 2 | Acceptance criteria verified against implementation | Developers | QA |
| 3 | Design fidelity reviewed | UI/UX Designer | Developers, QA |
| 4 | Test coverage confirmed (unit, integration, smoke) | Developers | QA |
| 5 | Metrics instrumentation verified and logging correctly | Developers | Data Analyst |

**Checklist:**
- [ ] All PRs merged and CI green
- [ ] Design review sign-off from UI/UX Designer
- [ ] QA test plan executed
- [ ] Data Analyst confirmed instrumentation is live

---

## QA → Release Handoff

| # | Handoff Item | Owner | Receiver |
|---|---|---|---|
| 1 | QA sign-off on acceptance criteria | QA | Release Manager |
| 2 | Release notes drafted | Product Manager, Release Manager | Stakeholders |
| 3 | Rollback plan documented | Release Manager | Developers, Operations |
| 4 | Deployment window confirmed | Release Manager | Project Manager |
| 5 | Stakeholder communication prepared | Project Manager, Release Manager | Stakeholders |

**Checklist:**
- [ ] QA sign-off received
- [ ] Release notes reviewed and approved
- [ ] Rollback steps documented and tested
- [ ] Deployment window communicated to all relevant parties
- [ ] Post-release monitoring plan in place

---

## Release → Post-Release / Retrospective Handoff

| # | Handoff Item | Owner | Receiver |
|---|---|---|---|
| 1 | Post-deploy verification completed | Release Manager, Developers | Project Manager |
| 2 | Release announcement sent | Project Manager, Release Manager | Stakeholders |
| 3 | Success metrics baseline captured | Data Analyst | Product Manager, Project Manager |
| 4 | Incident/rollback summary (if applicable) | Release Manager | All roles |
| 5 | Retrospective action items documented | Scrum Master, Project Manager | All roles |

**Checklist:**
- [ ] Post-deploy smoke tests passed
- [ ] Stakeholders notified of release outcome
- [ ] Success metrics dashboard updated
- [ ] Retrospective held and action items tracked in backlog

---

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
