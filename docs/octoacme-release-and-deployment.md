# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (confirmed by DevOps Engineer and Security Champion)
- Release notes drafted and reviewed by Documentation Lead
- Rollback / mitigation plan documented and reviewed by Release Manager
- Smoke tests prepared and assigned to QA
- Go/no-go sign-off obtained from PM, QA, and Release Manager

## Deployment Checklist
- [ ] Go/no-go decision confirmed (PM, QA, Release Manager)
- [ ] Deployment window scheduled and communicated to stakeholders
- [ ] Backup or snapshot taken (if applicable) — Owner: DevOps Engineer
- [ ] Release notes finalized and published — Owner: Documentation Lead
- [ ] Security scan results reviewed and no critical issues outstanding — Owner: Security Champion
- [ ] Deploy to staging and run smoke tests — Owner: DevOps Engineer + QA
- [ ] Staging smoke tests passed — Owner: QA
- [ ] Deploy to production (automated pipeline preferred) — Owner: DevOps Engineer
- [ ] Run post-deploy verifications — Owner: QA + DevOps Engineer
- [ ] Announce release to stakeholders and support — Owner: PM / Release Manager
- [ ] Monitor error rates and key metrics for 30 minutes post-deploy — Owner: DevOps Engineer

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call — Owner: DevOps Engineer
  - Notify PM and Release Manager immediately
  - Rollback to last known-good release if necessary — Owner: DevOps Engineer
  - Communicate status to stakeholders — Owner: PM / Release Manager
  - Triage root cause and capture action items — Owner: PM + DevOps Engineer
  - Schedule blameless post-mortem within 48 hours

## Release Notes Template
- Release name / number:
- Date:
- Author: (Documentation Lead)
- Reviewed by: (PM, QA)
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
- Rollback instructions (if needed):
