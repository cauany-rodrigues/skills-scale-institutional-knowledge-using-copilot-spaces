# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

### Role-Specific Escalation Paths
- **Technical blockers**: Developer → Tech Lead → Subject Matter Expert → Engineering Leadership
- **Design/UX issues**: UX/UI Designer → Product Manager → Design Lead
- **Infrastructure/deployment**: DevOps Engineer → Platform Team → Infrastructure Leadership
- **Quality/testing concerns**: QA Automation Engineer → QA Lead → Engineering Leadership
- **Documentation gaps**: Technical Writer → Product Manager → Documentation Lead
- **Domain/compliance**: Subject Matter Expert → Compliance Team → Legal/Regulatory

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Design reviews scheduled with UX/UI Designer (if applicable)
- [ ] Infrastructure and deployment readiness confirmed by DevOps Engineer
- [ ] Test automation coverage tracked by QA Automation Engineer
- [ ] Documentation progress tracked by Technical Writer
- [ ] SME reviews scheduled for domain-critical features

## Collaboration Review Checklists

### Design Implementation Review (Developer + UX/UI Designer)
- [ ] Design mockups reviewed and understood before implementation
- [ ] UI components match design specifications
- [ ] Accessibility requirements (WCAG) implemented
- [ ] Responsive design verified across breakpoints
- [ ] Design system components used consistently
- [ ] Edge cases and error states designed and implemented
- [ ] User feedback incorporated from usability testing

### Code Quality Review (Developer + QA Automation Engineer)
- [ ] Code follows team standards and best practices
- [ ] Unit tests written for new logic (>80% coverage target)
- [ ] Integration tests cover critical user flows
- [ ] Test data and mocks are maintainable
- [ ] Edge cases and error handling tested
- [ ] Performance considerations addressed
- [ ] Security best practices followed

### Infrastructure Review (Developer + DevOps Engineer)
- [ ] Infrastructure changes reviewed and approved
- [ ] CI/CD pipeline updated for new services or dependencies
- [ ] Environment variables and secrets managed securely
- [ ] Monitoring and alerting configured for new features
- [ ] Deployment plan documented and tested in staging
- [ ] Rollback plan verified and ready
- [ ] Resource scaling and performance validated

### Documentation Review (Developer + Technical Writer)
- [ ] API changes documented with examples
- [ ] User-facing features have corresponding user guides
- [ ] Internal documentation (runbooks, architecture) updated
- [ ] Code comments explain complex logic
- [ ] README and setup instructions are current
- [ ] Breaking changes clearly communicated
- [ ] Documentation published before or with release

### Domain Validation Review (Developer + Subject Matter Expert)
- [ ] Business logic aligns with domain requirements
- [ ] Compliance and regulatory requirements met
- [ ] Data validation rules are correct and complete
- [ ] Industry standards and best practices followed
- [ ] Security and privacy requirements addressed
- [ ] Edge cases specific to domain identified and handled
- [ ] Integration points with external systems validated
