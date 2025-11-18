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
  - **Security Lead**: Validates security scan results and approves security posture
- Release notes drafted
  - **Support Lead**: Reviews release notes for customer clarity
- Rollback / mitigation plan documented
  - **Operations Manager**: Prepares rollback procedures and infrastructure readiness
- Smoke tests prepared
  - **UX/UI Designer**: Validates critical user flows in staging

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
  - **Operations Manager**: Coordinates deployment timing and resource allocation
- [ ] Backup or snapshot (if applicable)
  - **Operations Manager**: Ensures backup and recovery procedures are ready
- [ ] Deploy to staging and run smoke tests
  - **Operations Manager**: Executes staging deployment
  - **UX/UI Designer**: Validates user interface and experience
- [ ] Deploy to production (automated pipeline preferred)
  - **Operations Manager**: Monitors deployment progress and system health
- [ ] Run post-deploy verifications
  - **Data Analyst**: Validates metrics and monitoring data collection
  - **Operations Manager**: Confirms system performance and stability
- [ ] Announce release to stakeholders and support
  - **Support Lead**: Notifies support team and prepares for customer questions
  - **Project Manager**: Sends stakeholder release notifications

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
    - **Operations Manager**: Leads technical incident response and coordinates rollback
    - **Security Lead**: Evaluates security implications of the incident
  - Rollback to last known-good release if necessary
    - **Operations Manager**: Executes rollback procedures
  - Triage root cause and capture action items
    - **Data Analyst**: Analyzes metrics to understand impact and root cause
  - **Support Lead**: Communicates with affected customers and manages support volume

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
