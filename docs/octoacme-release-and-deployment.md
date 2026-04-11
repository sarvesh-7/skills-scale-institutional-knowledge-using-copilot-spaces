# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- QA Engineer has completed formal quality sign-off
- Business Analyst has validated delivered features against original requirements
- Release notes drafted and reviewed by Technical Writer
- Rollback / mitigation plan documented
- Smoke tests prepared and executed by QA Engineer

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] QA Engineer quality sign-off received
- [ ] Business Analyst requirements validation complete
- [ ] Technical Writer has completed and published release notes
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Business Analyst conducts post-deployment validation with stakeholders
- [ ] Announce release to stakeholders and support (Technical Writer leads communication)

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
