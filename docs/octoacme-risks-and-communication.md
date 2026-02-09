# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner (assign to specific persona/role)
- Mitigation plan
- Status

### Sample Risk Assignments by Persona
- **Technical risks**: Developer or Subject Matter Expert
- **Design/UX risks**: UX/UI Designer or Product Manager
- **Infrastructure risks**: DevOps Engineer
- **Quality/testing risks**: QA Automation Engineer
- **Documentation risks**: Technical Writer
- **Compliance/regulatory risks**: Subject Matter Expert
- **Schedule/resource risks**: Project Manager
- **Product/market risks**: Product Manager

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- **Team-level** → **PM** → **Product Lead** → **Sponsor**
- For security incidents, follow the security incident runbook and notify Security on-call

### Detailed Escalation Matrix by Issue Type

**Technical/Engineering Issues:**
- Developer → Tech Lead → Subject Matter Expert (if specialized) → Engineering Manager → VP Engineering

**Design/User Experience Issues:**
- UX/UI Designer → Design Lead → Product Manager → Product Leadership

**Infrastructure/Platform Issues:**
- DevOps Engineer → Platform Team Lead → Infrastructure Manager → CTO

**Quality/Testing Issues:**
- QA Automation Engineer → QA Lead → Engineering Manager → VP Engineering

**Documentation Issues:**
- Technical Writer → Documentation Lead → Product Manager → Product Leadership

**Compliance/Regulatory Issues:**
- Subject Matter Expert → Compliance Officer → Legal → Executive Leadership

**Product/Scope Issues:**
- Product Manager → Product Leadership → Sponsor → Executive Steering Committee

**Project Timeline/Resource Issues:**
- Project Manager → Program Manager → Portfolio Manager → Executive Leadership

### Escalation Guidelines by Severity

**Severity 1 (Critical) - Immediate Escalation:**
- Production outage affecting customers
- Security breach or data loss
- Regulatory compliance violation
- **Action**: Escalate immediately to Level 2/3, notify all stakeholders

**Severity 2 (High) - Same-day Escalation:**
- Significant feature blocker
- Major performance degradation
- Critical dependency failure
- **Action**: Escalate within 4 hours, notify Project Manager and relevant leads

**Severity 3 (Medium) - Next-day Escalation:**
- Feature delay risk
- Minor integration issues
- Resource constraints
- **Action**: Raise in daily standup, escalate if unresolved in 24 hours

**Severity 4 (Low) - Weekly Escalation:**
- Nice-to-have feature concerns
- Minor documentation gaps
- Process improvement suggestions
- **Action**: Track in risk register, discuss in weekly syncs
