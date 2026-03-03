# Role Engagement Checklist

Use this checklist to confirm that the right roles are involved at the right time across the four main project phases.
Adapt entries to your project's size and risk level.

> **Reference:** See [octoacme-roles-and-personas.md](../octoacme-roles-and-personas.md) for full role descriptions.

---

## Phase 1 — Initiation

| # | Check | Responsible | Gate / Output |
|---|---|---|---|
| 1.1 | Problem statement and business case drafted | Product Manager | Project One-pager |
| 1.2 | Success metrics (KPIs) defined with Data Analyst | Product Manager + Data Analyst | KPI definition doc |
| 1.3 | Initial user-research questions scoped | UX Researcher | Research brief |
| 1.4 | Security requirements identified (data sensitivity, compliance scope) | Security Specialist | Security requirements list |
| 1.5 | Stakeholder list and communication plan created | Project Manager | Stakeholder register |
| 1.6 | Initial risk list reviewed, including security risks | Project Manager + Security Specialist | Risk register (draft) |
| 1.7 | Team roles confirmed (including UX, Security, Data, Scrum Master as needed) | Project Manager | Proposed team in One-pager |
| 1.8 | Go / No-go decision recorded | Project Sponsor + Project Manager | Decision log entry |

**Early-involvement gates:**
- [ ] UX Researcher briefed on target users and research constraints before planning begins
- [ ] Security Specialist consulted on data classification before architecture decisions are made
- [ ] Data Analyst aligned on measurement approach before success metrics are finalized

---

## Phase 2 — Planning

| # | Check | Responsible | Gate / Output |
|---|---|---|---|
| 2.1 | Backlog items created with acceptance criteria | Product Manager + Developers | Prioritized backlog |
| 2.2 | UX research plan and usability test schedule drafted | UX Researcher | UX plan |
| 2.3 | Threat model completed for new features/integrations | Security Specialist + Developers | Threat model document |
| 2.4 | KPI instrumentation events specified | Data Analyst + Developers | Tracking specification |
| 2.5 | Definition of Done updated to include UX and security criteria | Scrum Master + Team | Updated DoD |
| 2.6 | Sprint calendar and team capacity confirmed | Scrum Master + Project Manager | Sprint plan |
| 2.7 | Release plan and milestones agreed | Project Manager | Release plan |
| 2.8 | Cross-team dependencies identified and owners assigned | Project Manager + Scrum Master | Dependency log |

**Early-involvement gates:**
- [ ] Threat modeling session held **before** implementation begins (Security Specialist facilitates)
- [ ] KPI measurement plan reviewed and approved before instrumentation is coded (Data Analyst)
- [ ] Usability test plan scheduled at least one sprint before code-complete (UX Researcher)

---

## Phase 3 — Execution

| # | Check | Responsible | Gate / Output |
|---|---|---|---|
| 3.1 | Daily standups facilitated and blockers logged | Scrum Master | Impediment log |
| 3.2 | UX research sessions conducted and findings shared | UX Researcher | Research readout |
| 3.3 | Security code reviews performed for high-risk changes | Security Specialist + Developers | Review comments / sign-off |
| 3.4 | Data collection events verified in staging environment | Data Analyst + Developers | Instrumentation sign-off |
| 3.5 | Sprint velocity and burndown tracked and reported | Scrum Master | Sprint metrics |
| 3.6 | Usability test conducted and issues prioritized | UX Researcher + Product Manager | Usability findings report |
| 3.7 | Security scan results reviewed; critical findings remediated | Security Specialist | Scan report + issue list |
| 3.8 | Risk register reviewed and updated weekly | Project Manager | Updated risk register |
| 3.9 | Retrospectives held each sprint; actions captured | Scrum Master | Retrospective action items |

**Early-involvement gates:**
- [ ] Security Specialist reviews any new external dependency or API integration before merging
- [ ] Data Analyst confirms tracking events fire correctly in staging before release branch is cut
- [ ] UX Researcher findings fed back into backlog within same sprint cycle

---

## Phase 4 — Release

| # | Check | Responsible | Gate / Output |
|---|---|---|---|
| 4.1 | All acceptance criteria met and verified | Developers + QA | QA sign-off |
| 4.2 | Security pre-release review completed and approved | Security Specialist | Security sign-off |
| 4.3 | KPI dashboards live and baseline metrics captured | Data Analyst | Dashboard link |
| 4.4 | Release notes drafted and reviewed | Product Manager + Project Manager | Release notes |
| 4.5 | Rollback plan documented and tested | Developers + Project Manager | Rollback runbook |
| 4.6 | Stakeholder announcement prepared | Project Manager | Announcement draft |
| 4.7 | Post-release monitoring plan confirmed | Data Analyst + Developers | Monitoring checklist |
| 4.8 | Post-launch retrospective scheduled | Scrum Master | Calendar invite |

**Early-involvement gates:**
- [ ] Security Specialist provides mandatory sign-off **before** production deployment (see [octoacme-release-and-deployment.md](../octoacme-release-and-deployment.md))
- [ ] Data Analyst confirms dashboards and alerts are ready **before** announcing to stakeholders
- [ ] UX Researcher schedules post-launch usability feedback collection within first two weeks

---

## Quick Reference — Role Engagement by Phase

| Role | Initiation | Planning | Execution | Release |
|---|---|---|---|---|
| Product Manager | ✅ Lead | ✅ Lead | ✅ Consult | ✅ Review |
| Project Manager | ✅ Lead | ✅ Lead | ✅ Coordinate | ✅ Lead |
| Developers | 🔵 Consult | ✅ Participate | ✅ Lead | ✅ Lead |
| QA | 🔵 Consult | 🔵 Consult | ✅ Participate | ✅ Sign-off |
| UX Researcher | ✅ **Early** | ✅ Lead | ✅ Participate | 🔵 Consult |
| Security Specialist | ✅ **Early** | ✅ **Gate** | ✅ Review | ✅ **Gate** |
| Data Analyst | ✅ **Early** | ✅ Lead | ✅ Verify | ✅ Monitor |
| Scrum Master | 🔵 Consult | ✅ Facilitate | ✅ Lead | 🔵 Consult |
| Stakeholders | ✅ Inform | ✅ Inform | 🔵 Escalation | ✅ Inform |

**Legend:**
- ✅ Active involvement required
- ✅ **Early** / **Gate** — Must be engaged **before** the phase proceeds; blocking gate if absent
- 🔵 Consulted or informed as needed
