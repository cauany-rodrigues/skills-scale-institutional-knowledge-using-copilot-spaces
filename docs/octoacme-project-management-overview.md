# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **UX/UI Designer**: designs user experiences, creates mockups, ensures accessibility.
- **DevOps Engineer**: manages infrastructure, CI/CD pipelines, and deployment automation.
- **QA Automation Engineer**: creates automated tests, validates quality, ensures release readiness.
- **Technical Writer**: creates documentation, user guides, and API references.
- **Subject Matter Expert (SME)**: provides domain expertise, validates requirements, reviews technical decisions.
- **Stakeholders**: provide inputs and approvals.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.

## Role-Specific Project Management Checklists

### Product Manager Checklist
- [ ] Define clear problem statement and success metrics
- [ ] Prioritize backlog items based on customer value and business impact
- [ ] Review and approve acceptance criteria with the team
- [ ] Validate designs and prototypes align with user needs
- [ ] Monitor product metrics and KPIs post-release
- [ ] Gather user feedback and iterate on features
- [ ] Participate in retrospectives and contribute improvement ideas

### Project Manager Checklist
- [ ] Create and maintain project timeline and milestones
- [ ] Facilitate kickoff, planning, and retrospective meetings
- [ ] Update and communicate project status weekly
- [ ] Track and escalate risks, blockers, and dependencies
- [ ] Ensure all documentation is current and accessible
- [ ] Coordinate cross-team dependencies and approvals
- [ ] Review project artifacts before major milestones

### Developer Checklist
- [ ] Understand acceptance criteria before starting work
- [ ] Write clean, testable, and well-documented code
- [ ] Submit PRs with clear descriptions and test coverage
- [ ] Participate in code reviews and address feedback promptly
- [ ] Collaborate with UX/UI Designer on implementation details
- [ ] Assist QA with bug reproduction and fixes
- [ ] Update technical documentation as needed
- [ ] Attend standups and communicate blockers early

### UX/UI Designer Checklist
- [ ] Conduct user research to inform design decisions
- [ ] Create wireframes and mockups for review and approval
- [ ] Ensure designs meet accessibility (WCAG) standards
- [ ] Collaborate with Developers on design handoff and implementation
- [ ] Review UI implementation for design fidelity
- [ ] Participate in usability testing and gather feedback
- [ ] Maintain design system components and documentation
- [ ] Support Product Manager with user insights and data

### DevOps Engineer Checklist
- [ ] Set up and maintain CI/CD pipelines for the project
- [ ] Configure infrastructure and environments (dev, staging, prod)
- [ ] Implement monitoring, logging, and alerting systems
- [ ] Document deployment procedures and rollback plans
- [ ] Review and approve infrastructure changes
- [ ] Support release deployments and post-deploy verification
- [ ] Respond to incidents and conduct root cause analysis
- [ ] Optimize infrastructure costs and performance

### QA Automation Engineer Checklist
- [ ] Review acceptance criteria and create test plans
- [ ] Design and implement automated test suites (unit, integration, e2e)
- [ ] Integrate tests into CI/CD pipelines
- [ ] Execute exploratory testing for edge cases
- [ ] Report bugs with clear reproduction steps and severity
- [ ] Monitor test coverage and quality metrics
- [ ] Validate fixes and sign off on release readiness
- [ ] Collaborate with Developers on testability improvements

### Technical Writer Checklist
- [ ] Review feature specs and understand user workflows
- [ ] Create or update user guides, API docs, and tutorials
- [ ] Validate documentation accuracy with SMEs and Developers
- [ ] Ensure consistent terminology and style across docs
- [ ] Review UI text and error messages for clarity
- [ ] Publish documentation before or with feature release
- [ ] Gather feedback and iterate on content based on user needs
- [ ] Maintain documentation site structure and navigation

### Subject Matter Expert Checklist
- [ ] Review requirements for domain-specific accuracy and compliance
- [ ] Provide guidance on technical architecture and design decisions
- [ ] Validate test scenarios cover domain-critical functionality
- [ ] Identify risks related to specialized areas (security, regulations, etc.)
- [ ] Conduct knowledge-sharing sessions with the team
- [ ] Review technical documentation for accuracy
- [ ] Stay current with industry standards and regulatory changes
- [ ] Escalate concerns that impact compliance or domain integrity

### Cross-Functional Collaboration Checklist
- [ ] All roles: Attend scheduled standups and team meetings
- [ ] All roles: Update project board with task status regularly
- [ ] All roles: Raise blockers and dependencies promptly
- [ ] All roles: Participate in retrospectives and suggest improvements
- [ ] Developers & QA: Collaborate on test strategy and coverage
- [ ] Developers & UX/UI Designer: Review designs before and during implementation
- [ ] DevOps & Developers: Coordinate on deployment and infrastructure needs
- [ ] Technical Writer & SME: Ensure documentation accuracy and completeness
- [ ] Product Manager & Project Manager: Align on priorities and timelines weekly
- [ ] Project Manager: Facilitate communication between all roles and stakeholders
