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
  - **UX/UI Designer**: Validates user experience and accessibility in testing
- Security scanning in CI
  - **Security Lead**: Reviews security scan results and ensures vulnerabilities are addressed
- Manual QA for feature acceptance when needed
  - **Support Lead**: Provides customer perspective during QA and validates documentation

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
  - **Data Analyst**: Creates and maintains dashboards for key metrics
  - **Data Analyst**: Provides regular analysis and insights on product performance
- Use dashboards for key signals (errors, latency, usage)
  - **Operations Manager**: Monitors system performance and operational metrics
  - **Support Lead**: Tracks support volume and customer satisfaction metrics

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- **Security Lead**: Escalates security and compliance blockers through security channels
- **Operations Manager**: Escalates infrastructure and availability blockers
- **Support Lead**: Escalates customer-critical issues requiring immediate attention

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
