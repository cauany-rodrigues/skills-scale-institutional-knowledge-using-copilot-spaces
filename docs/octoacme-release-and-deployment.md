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
- Release notes drafted by Technical Writer
- Rollback / mitigation plan documented by DevOps Engineer
- Smoke tests prepared by QA Automation Engineer
- UX/UI Designer sign-off on user-facing changes (if applicable)
- Subject Matter Expert approval for domain-critical changes (if applicable)
- Documentation published by Technical Writer

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

### Role-Specific Deployment Responsibilities

**DevOps Engineer:**
- [ ] Execute deployment to staging and production
- [ ] Monitor deployment progress and health checks
- [ ] Verify infrastructure scaling and performance
- [ ] Be ready to execute rollback if needed
- [ ] Validate monitoring and alerting are functioning

**QA Automation Engineer:**
- [ ] Run automated smoke tests in staging
- [ ] Execute critical user flow validation in production
- [ ] Verify test environment stability post-deployment
- [ ] Monitor for quality regressions
- [ ] Sign off on deployment quality gate

**Developer:**
- [ ] Final code review and merge
- [ ] Be available during deployment window for support
- [ ] Monitor application logs for errors
- [ ] Respond to any technical issues during deployment

**Product Manager:**
- [ ] Approve final release scope
- [ ] Coordinate with stakeholders on timing
- [ ] Prepare internal announcement
- [ ] Monitor user feedback and metrics post-release

**Project Manager:**
- [ ] Coordinate deployment timeline and communications
- [ ] Ensure all pre-release checklist items completed
- [ ] Facilitate go/no-go decision
- [ ] Track deployment status and update stakeholders

**UX/UI Designer:**
- [ ] Verify UI changes in staging match designs
- [ ] Validate responsive design in production
- [ ] Check accessibility features are working
- [ ] Monitor user experience metrics post-release

**Technical Writer:**
- [ ] Publish updated documentation before deployment
- [ ] Verify documentation links and screenshots are current
- [ ] Prepare user communication about new features
- [ ] Update help center and support articles

**Subject Matter Expert:**
- [ ] Final validation of domain-specific functionality in staging
- [ ] Verify compliance requirements are met
- [ ] Review release notes for accuracy
- [ ] Be available for escalation during deployment

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary (DevOps Engineer executes)
  - Triage root cause and capture action items
  - Communicate status to stakeholders (Project Manager leads)

### Incident Response by Role

**DevOps Engineer (Incident Commander for infrastructure issues):**
- Execute rollback procedure
- Investigate infrastructure and deployment logs
- Restore service availability
- Document timeline and technical details

**Developer (Incident Commander for application issues):**
- Investigate application logs and errors
- Identify root cause of application failures
- Implement hotfix if rollback is not sufficient
- Create post-incident bug fixes

**QA Automation Engineer:**
- Validate rollback was successful
- Test critical user flows after rollback/fix
- Identify why issue wasn't caught in testing
- Recommend additional test coverage

**Product Manager:**
- Assess customer impact and prioritize response
- Communicate with affected customers if needed
- Decide on feature rollback vs. hotfix
- Coordinate with support team

**Project Manager:**
- Coordinate incident response across teams
- Communicate status updates to leadership
- Track incident timeline and actions
- Schedule post-incident retrospective

**Subject Matter Expert:**
- Validate compliance implications of incident
- Review if domain-specific requirements were violated
- Advise on regulatory reporting needs
- Provide domain expertise for root cause analysis

**Technical Writer:**
- Update documentation if incident revealed gaps
- Communicate known issues to users if needed
- Update runbooks based on incident learnings
- Publish post-incident user communication

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
