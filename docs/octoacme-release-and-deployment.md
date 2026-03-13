# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Owners & Responsibilities

| Release Task                        | Owner        | Approver (Major) |
|-------------------------------------|--------------|-----------------|
| Prepare release notes               | Developer    | PM              |
| Run smoke tests (staging)           | QA Lead      | QA Lead         |
| QA sign-off confirmation            | QA Lead      | QA Lead         |
| Deploy to staging                   | Developer    | PM              |
| Deploy to production                | Developer    | PM              |
| Post-deploy verification            | QA Lead      | PM              |
| Stakeholder / support notification  | PM           | PM              |
| Sponsor notification (Major only)   | PM           | Sponsor         |

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] **QA Lead sign-off received** (written confirmation)
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] **Sponsor notified** (Major releases only)

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
