# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Ownership
The **Release Manager** coordinates all release activities, working with Product Managers, Developers, and stakeholders to ensure successful deployments.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by **Security Lead**)
- Release notes drafted (coordinated by **Release Manager**)
- Rollback / mitigation plan documented (owned by **Release Manager**)
- Smoke tests prepared
- **Support Lead** briefed on changes and customer impact
- **Data Analyst** confirms tracking instrumentation is in place

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — **Release Manager**
- [ ] Security scans reviewed and approved — **Security Lead**
- [ ] Backup or snapshot (if applicable) — **Release Manager**
- [ ] Deploy to staging and run smoke tests — **Release Manager** with **Developers**
- [ ] Support team briefed on changes — **Release Manager** to **Support Lead**
- [ ] Deploy to production (automated pipeline preferred) — **Release Manager**
- [ ] Run post-deploy verifications — **Developers** and **Release Manager**
- [ ] Announce release to stakeholders and support — **Release Manager** with **Product Manager**
- [ ] Monitor metrics and dashboards — **Data Analyst** and **Support Lead**

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - **Release Manager** triggers incident response and notifies on-call
  - **Support Lead** monitors customer impact and coordinates communication
  - **Release Manager** executes rollback to last known-good release if necessary
  - **Developers** and **Security Lead** triage root cause
  - **Project Manager** captures action items for retrospective
  - **Data Analyst** tracks incident metrics and impact

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
