# OctoAcme — Roles & RACI Matrix

## Purpose
Provide a lightweight accountability reference showing which roles are **Responsible**, **Accountable**, **Consulted**, or **Informed** for key activities across the project lifecycle.

> **RACI key**
> - **R** = Responsible — does the work
> - **A** = Accountable — owns the outcome; approves deliverables (one per activity)
> - **C** = Consulted — provides input before or during the work
> - **I** = Informed — kept up to date on progress or decisions

---

## Project Lifecycle RACI

| Activity | Project Manager | Product Manager | Developer | QA / Test Engineer | Engineering Manager | Designer / UX | Delivery Lead | Tech Lead / Architect | Stakeholder / Sponsor | Support / CS | Security / Compliance | DevOps / Platform |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** | | | | | | | | | | | | |
| Define problem statement & success metrics | C | **A** | I | I | C | C | | C | C | C | | |
| Create Project One-pager / Charter | **A** | R | I | | I | | | C | C | | C | |
| Stakeholder identification & communication plan | **A** | R | | | | | | | C | C | | |
| Initial risk identification | **A** | C | C | | C | | | C | I | | C | |
| Go / No-go decision for planning | C | C | | | C | | | C | **A** | | | |
| **Planning** | | | | | | | | | | | | |
| Backlog creation & prioritization | C | **A** | C | C | C | C | R | C | I | C | | |
| Acceptance criteria definition | C | **A** | C | C | | R | | | I | | | |
| Test strategy & test plan | C | C | C | **A** | | | | C | | | C | |
| Architecture & technical design | C | C | C | | C | | | **A** | | | C | C |
| Release plan & milestone map | **A** | C | C | C | C | | R | C | I | I | | C |
| Definition of Done (DoD) | C | C | R | R | C | | **A** | C | | | | |
| Security requirements definition | C | C | | C | | | | C | | | **A** | C |
| **Execution & Tracking** | | | | | | | | | | | | |
| Sprint / iteration planning | C | C | R | C | I | C | **A** | C | | | | |
| Feature implementation | | C | **A** | C | | C | | C | | | | |
| Code review | | | R | | | | | **A** | | | C | |
| Test execution & defect triage | | C | R | **A** | | | | C | | | | |
| Progress reporting & risk updates | **A** | C | I | I | C | | C | C | I | | | |
| Blocker escalation | **A** | C | C | | C | | R | C | C | | | |
| **Release & Deployment** | | | | | | | | | | | | |
| Release readiness sign-off | **A** | C | C | R | C | | | C | I | C | R | C |
| Deployment execution | C | | R | | | | | C | | | C | **A** |
| Smoke tests & post-deploy verification | | | R | **A** | | | | C | | | | C |
| Rollback planning & execution | C | | C | | | | | C | | | | **A** |
| Release announcement | C | **A** | | | | | | | I | R | | |
| Support & customer communication | C | C | | | | | | | I | **A** | | |
| **Retrospective & Close** | | | | | | | | | | | | |
| Retrospective facilitation | C | C | I | I | I | I | **A** | I | | | | |
| Action item definition & tracking | **A** | C | C | C | C | | R | C | | | | |
| Lessons learned documentation | **A** | C | C | C | | | R | C | I | C | | |

---

## Notes on applying this matrix

1. **One A per row.** If you find yourself assigning A to multiple roles, clarify who has final sign-off authority before work begins.
2. **Adapt for team size.** On smaller teams, one person may hold multiple role columns. Ensure every A has a named owner even when roles merge.
3. **Use it in kickoffs.** Walk through the relevant rows at project kickoff to align on ownership before problems arise.
4. **Keep it living.** Update the matrix when team structure or project phase changes—especially before major releases.

---

## Cross-role handoff guide

The following handoffs are most commonly where accountability gaps appear. Clarify these explicitly at project start.

| Handoff | From | To | Key checkpoint |
|---|---|---|---|
| Feature ready for QA | Developer | QA / Test Engineer | Acceptance criteria met, PR merged, feature deployed to test environment |
| Test sign-off for release | QA / Test Engineer | Project Manager | Test report reviewed, blocking defects resolved |
| Release readiness approval | Project Manager + QA + Security | DevOps / Platform Engineer | All pre-release checklist items complete |
| Customer rollout communication | Project Manager | Support / Customer Success | Release notes finalized, support trained |
| Post-release incident response | DevOps / Platform Engineer | Support / Customer Success + Project Manager | Incident severity assessed, customer impact confirmed |
| Architecture decision approval | Technical Lead / Architect | Developer | ADR documented and team aligned before implementation |
| Security review clearance | Security / Compliance | Technical Lead + Project Manager | Security findings resolved or formally accepted with mitigation |

---

*For full role definitions, see [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md).*
