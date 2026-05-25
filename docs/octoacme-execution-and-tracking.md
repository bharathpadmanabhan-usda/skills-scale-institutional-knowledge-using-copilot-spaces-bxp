# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI (maintained by DevOps Engineer)
- QA Automation Engineer maintains regression suites and integrates them into CI pipelines
- Manual QA for feature acceptance when needed
- UX/UI Designer performs design QA on implemented front-end features before sprint review
- Accessibility checks included as part of the Definition of Done for user-facing changes

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer owns pipeline setup)
- [ ] Automated regression suite integrated into CI (QA Automation Engineer)
- [ ] Design specs (wireframes/prototypes) handed off to Developers before sprint start (UX/UI Designer)
- [ ] Design QA completed by UX/UI Designer before sprint demo
- [ ] Business Analyst available to clarify requirements and review acceptance criteria during the sprint
- [ ] Regular demos scheduled
- [ ] Support/Operations (SRE) notified of in-flight changes with operational risk noted
- [ ] Risk register updated weekly
