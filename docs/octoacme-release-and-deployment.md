# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (confirmed by DevOps Engineer)
- QA Automation Engineer confirms all automated regression tests pass
- UX/UI Designer sign-off on user-facing changes
- Business Analyst confirms delivered solution meets documented requirements
- Release notes drafted
- Rollback / mitigation plan documented and reviewed with DevOps Engineer and Support/Operations (SRE)
- Smoke tests prepared
- Support/Operations (SRE) briefed on the release and updated runbooks/alerts ready

## Deployment Checklist
- [ ] Deployment window scheduled and communicated (PM coordinates with DevOps Engineer)
- [ ] DevOps Engineer confirms pipeline and infrastructure readiness
- [ ] QA Automation Engineer confirms all automated tests pass in staging
- [ ] UX/UI Designer has completed design QA on all user-facing changes
- [ ] Business Analyst has validated acceptance criteria are met
- [ ] Support/Operations (SRE) has reviewed release notes and updated monitoring/alerting
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
