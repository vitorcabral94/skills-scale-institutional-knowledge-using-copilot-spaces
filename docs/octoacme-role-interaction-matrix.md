# OctoAcme Role Interaction Matrix

This document provides a consolidated view of how all OctoAcme roles interact across the project lifecycle. Use it alongside [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) for role definitions.

---

## RACI Key

| Symbol | Meaning |
|---|---|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome and makes final decisions |
| **C** | Consulted — provides input before or during the work |
| **I** | Informed — kept up to date on progress or decisions |

---

## RACI Matrix by Lifecycle Phase

> **Column abbreviations:** PM = Project Manager · PdM = Product Manager · Tech Lead = Technical Lead · Eng Mgr = Engineering Manager · Dev = Developers · QA = QA/Testing · UX/UI = UX/UI Designer · DevOps = DevOps/Platform Engineer · BA = Business Analyst · CS = Customer Success/Support Liaison · Sec = Security/Compliance Representative

### 1. Project Initiation

| Activity | PM | PdM | Tech Lead | Eng Manager | Dev | QA | UX/UI | DevOps | BA | Customer Success | Security |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Define problem statement & SMART objective | C | A/R | C | I | I | I | C | I | C | C | I |
| Stakeholder identification & alignment | A/R | C | I | I | I | I | I | I | C | C | I |
| Project charter / one-pager creation | A/R | C | C | C | I | I | C | I | R | I | C |
| Go/no-go decision gate | A | A | C | C | I | I | I | I | I | I | C |
| Security & compliance scoping | I | C | C | I | I | I | I | I | I | I | A/R |

### 2. Project Planning

| Activity | PM | PdM | Tech Lead | Eng Manager | Dev | QA | UX/UI | DevOps | BA | Customer Success | Security |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Backlog creation & prioritization | C | A/R | C | C | C | C | C | C | C | C | C |
| Acceptance criteria definition | C | A | C | I | C | C | C | I | R | C | C |
| Technical design & architecture | I | C | A/R | C | R | C | C | C | I | I | C |
| Effort estimation | C | C | A/R | C | R | C | C | C | C | I | I |
| Capacity & resource planning | A/R | C | C | A/R | I | I | I | I | I | I | I |
| UX/UI design & specifications | I | C | C | I | I | C | A/R | I | I | C | I |
| Release & milestone mapping | A/R | C | C | C | I | I | I | C | I | I | C |
| Definition of Done finalization | A/R | C | C | I | C | C | C | I | C | I | C |
| Risk register initialization | A/R | C | C | C | C | C | C | C | C | C | C |

### 3. Execution & Tracking

| Activity | PM | PdM | Tech Lead | Eng Manager | Dev | QA | UX/UI | DevOps | BA | Customer Success | Security |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Feature development | I | C | C | I | A/R | C | C | C | I | I | I |
| Code review & quality enforcement | I | I | A/R | I | R | I | I | I | I | I | C |
| QA testing & bug tracking | I | C | C | I | C | A/R | I | I | I | I | C |
| Security review of changes | I | I | C | I | C | C | I | C | I | I | A/R |
| Blocker resolution | A/R | C | C | C | R | C | C | C | C | I | C |
| Standup & delivery sync facilitation | A/R | C | C | I | I | I | I | I | I | I | I |
| Scope change assessment | A | A | C | C | C | C | C | C | R | C | C |
| Risk register updates | A/R | C | C | C | C | C | C | C | C | C | C |
| Status reporting to stakeholders | A/R | C | I | I | I | I | I | I | I | I | I |

### 4. Release & Deployment

| Activity | PM | PdM | Tech Lead | Eng Manager | Dev | QA | UX/UI | DevOps | BA | Customer Success | Security |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Release readiness checklist sign-off | A/R | C | C | I | C | C | I | C | I | C | C |
| Deployment execution | I | I | C | I | C | I | I | A/R | I | I | I |
| Smoke testing & post-deploy verification | I | I | C | I | C | A/R | I | C | I | I | C |
| Rollback decision & execution | A | C | C | I | C | I | I | A/R | I | I | C |
| Release notes & customer communication | C | C | I | I | I | I | I | I | C | A/R | I |
| Compliance/security release sign-off | I | I | C | I | I | I | I | C | I | I | A/R |

### 5. Retrospective & Improvement

| Activity | PM | PdM | Tech Lead | Eng Manager | Dev | QA | UX/UI | DevOps | BA | Customer Success | Security |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Retrospective facilitation | A/R | C | C | C | I | I | I | I | I | I | I |
| Action item creation & ownership | A/R | C | C | C | C | C | C | C | C | C | C |
| Post-release metrics review | C | A/R | C | I | I | I | I | I | I | C | I |
| Process improvement proposals | C | C | C | C | R | R | R | R | R | R | R |
| Customer feedback incorporation | I | A/R | I | I | I | I | C | I | C | R | I |

---

## Role Handoff Checklist

Use this checklist to ensure clean handoffs between roles at key transition points in the lifecycle.

### Initiation → Planning Handoff

- [ ] Project charter reviewed and go/no-go decision recorded
- [ ] Problem statement, objective, and success metrics confirmed with Product Manager
- [ ] Initial stakeholder list and RACI shared with team
- [ ] Business Analyst briefed on requirements scope and engagement model
- [ ] Security/Compliance Representative engaged if regulatory or privacy scope identified
- [ ] Technical Lead briefed on project context and asked to review architectural assumptions

### Planning → Execution Handoff

- [ ] Backlog prioritized with acceptance criteria on all sprint-ready items
- [ ] UX/UI design assets available for all items entering the first sprint
- [ ] Technical design or ADR completed for all complex/high-risk items
- [ ] Definition of Done documented and shared with Developers and QA
- [ ] CI/CD pipeline and staging environment confirmed ready by DevOps/Platform Engineer
- [ ] QA test plan or test strategy documented for the release
- [ ] Security review requirements identified for relevant features

### Execution → Release Handoff

- [ ] All acceptance criteria verified by QA and accepted by Product Manager
- [ ] Security review completed and sign-off obtained from Security/Compliance Representative
- [ ] Deployment runbook reviewed and confirmed by DevOps/Platform Engineer
- [ ] Rollback plan documented and shared with PM and DevOps
- [ ] Release notes drafted and reviewed by Customer Success/Support Liaison
- [ ] Smoke test suite updated to cover new flows
- [ ] Stakeholders notified of release timing and scope via PM

### Post-Release / Retrospective Handoff

- [ ] Post-deploy metrics reviewed (error rates, latency, adoption signals)
- [ ] Customer Success/Support Liaison monitoring for new support trends
- [ ] Retrospective scheduled within one week of release
- [ ] Action items assigned to named owners with target dates
- [ ] Lessons learned documented and linked from the project artifact log

---

## Cross-Role Decision Guide

Use this guide to quickly identify who should be involved in common project decisions.

| Decision Type | Accountable | Must Consult | Must Inform |
|---|---|---|---|
| Scope change (minor) | PM | PdM, Tech Lead | Developers, QA |
| Scope change (major) | PdM + PM | Tech Lead, Eng Manager, BA | All roles |
| Architecture change | Tech Lead | PM, PdM, DevOps, Security | Developers, QA |
| Release delay | PM | PdM, Tech Lead, Eng Manager | Stakeholders, Customer Success |
| Priority re-ordering | PdM | PM, BA, Customer Success | Developers, QA |
| Security/compliance risk escalation | Security Rep | PM, PdM, Tech Lead | Eng Manager, Stakeholders (via PM) |
| Team capacity reduction | Eng Manager | PM, PdM | Stakeholders (via PM) |
| Rollback decision | PM | Tech Lead, DevOps | PdM, QA, Customer Success, Stakeholders |
| New tooling or platform change | Tech Lead | DevOps, Eng Manager, PM | Developers, QA |
| Customer-reported critical defect | PM | PdM, Tech Lead, Customer Success | QA, Developers, Security (if security-related) |

---

## Reference

- [Roles & Personas](octoacme-roles-and-personas.md) — detailed responsibilities and goals for each role
- [Project Management Overview](octoacme-project-management-overview.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
