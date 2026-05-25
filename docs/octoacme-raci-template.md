# OctoAcme — RACI Matrix Template

## Purpose
Clarify cross-role responsibilities at each stage of the project lifecycle to eliminate ambiguity, reduce duplicated effort, and ensure every activity has a clear owner.

## How to Use This Template
1. Copy the sample matrix below into your project documentation.
2. Adjust roles and activities to match your project's scope.
3. Review the RACI with the full team during kickoff or planning.
4. Update the matrix when scope or team composition changes.

## RACI Key

| Symbol | Meaning |
|--------|---------|
| **R** | **Responsible** – Does the work to complete the activity |
| **A** | **Accountable** – Ultimately answerable for the activity; approves the output (only one per row) |
| **C** | **Consulted** – Provides input, expertise, or review; two-way communication |
| **I** | **Informed** – Kept up-to-date on progress or decisions; one-way communication |

---

## Sample RACI Matrix

> **Roles:** PM = Project Manager · PdM = Product Manager · Dev = Developer · UX = UX/UI Designer · BA = Business Analyst · DevOps = DevOps Engineer · QAE = QA Automation Engineer · QA = QA/Testing · SRE = Support/Operations (SRE) · Stakeholder

| # | Activity / Deliverable | PM | PdM | Dev | UX | BA | DevOps | QAE | QA | SRE | Stakeholder |
|---|------------------------|-----|-----|-----|----|----|--------|-----|----|-----|-------------|
| **Initiation** |
| 1 | Define problem statement and goals | C | A | I | I | C | I | I | I | I | C |
| 2 | Create Project One-pager | A | R | I | C | C | I | I | I | I | C |
| 3 | Identify team roles and resource needs | A | C | C | C | C | C | C | C | C | I |
| 4 | Stakeholder alignment and go/no-go decision | R | C | I | I | I | I | I | I | I | A |
| **Planning** |
| 5 | Requirements gathering and documentation | C | C | C | C | A/R | I | I | C | I | C |
| 6 | Backlog creation and prioritization | C | A | C | C | R | I | I | C | I | I |
| 7 | UX design review and wireframe sign-off | C | A | C | R | C | I | I | I | I | I |
| 8 | Definition of Done (DoD) definition | A | C | R | C | C | C | C | C | I | I |
| 9 | Test plan and automation strategy | C | I | C | I | C | C | A/R | C | I | I |
| 10 | Infrastructure and pipeline planning | C | I | C | I | I | A/R | C | I | C | I |
| 11 | Release plan and milestone map | A | C | C | C | C | C | C | C | C | I |
| **Execution** |
| 12 | Feature development and code review | I | I | A/R | C | I | C | C | I | I | I |
| 13 | Design handoff and design QA | I | C | C | A/R | I | I | I | C | I | I |
| 14 | Automated test development and maintenance | I | I | C | I | I | C | A/R | C | I | I |
| 15 | CI/CD pipeline management and environment provisioning | I | I | C | I | I | A/R | C | I | C | I |
| 16 | Sprint review / demo facilitation | A | C | R | R | C | I | I | R | I | C |
| 17 | Risk register update | A | C | C | I | C | C | I | I | C | I |
| **Release** |
| 18 | Pre-release readiness sign-off | A | C | C | C | C | C | C | C | C | I |
| 19 | Deployment to staging and production | C | I | C | I | I | A/R | C | C | C | I |
| 20 | Post-deploy smoke tests | C | I | C | I | I | C | A/R | R | C | I |
| 21 | Release notes and stakeholder communication | A | C | C | I | C | I | I | I | C | I |
| 22 | Rollback decision and execution | A | C | C | I | I | R | C | C | C | I |
| **Post-Release & Retrospective** |
| 23 | Production monitoring and incident response | I | I | C | I | I | C | I | I | A/R | I |
| 24 | Post-incident review / post-mortem | C | I | R | I | I | R | C | C | A | I |
| 25 | Retrospective facilitation | A/R | C | C | C | C | C | C | C | C | I |
| 26 | Action item tracking and follow-up | A | C | C | C | C | C | C | C | C | I |
| 27 | Lessons learned documentation | A | C | R | C | C | C | C | C | C | I |

---

## Notes and Guidance

- **One Accountable per row:** Avoid assigning "A" to more than one role per activity to maintain clear ownership.
- **Avoid over-consulting:** Limit "C" assignments to roles that genuinely need to provide input. Over-consulting slows decisions.
- **Revisit regularly:** Update this matrix if team composition or project scope changes.
- **Use in onboarding:** Share this matrix with new team members to help them quickly understand their responsibilities.

## Related Documents
- [Roles and Personas](./octoacme-roles-and-personas.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
