# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (monitored by DevOps Engineer)
- Release notes drafted (Technical Writer)
- User documentation updated (Technical Writer)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared (QA/Testing with DevOps Engineer)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — coordinated by PM and DevOps Engineer
- [ ] Backup or snapshot (if applicable) — DevOps Engineer
- [ ] Deploy to staging and run smoke tests — DevOps Engineer with QA/Testing
- [ ] Deploy to production (automated pipeline preferred) — DevOps Engineer
- [ ] Run post-deploy verifications — DevOps Engineer and QA/Testing
- [ ] Announce release to stakeholders and support — Technical Writer and Product Manager

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads)
  - Rollback to last known-good release if necessary (DevOps Engineer executes)
  - Triage root cause and capture action items (coordinated by Scrum Master or PM)
  - Update runbooks and documentation (Technical Writer)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
