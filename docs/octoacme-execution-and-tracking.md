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
- Security scanning in CI (reviewed by **Security Lead**)
- Manual QA for feature acceptance when needed
- **UX Designer** validates design implementation
- Accessibility testing for user-facing features

## Reporting & Metrics
- Track velocity and burndown (**Project Manager**)
- Monitor success metrics identified in the Project One-pager (**Product Manager** with **Data Analyst**)
- Use dashboards for key signals (errors, latency, usage) — **Data Analyst** maintains dashboards
- **Data Analyst** provides weekly metrics reviews and insights
- **Support Lead** reports on customer feedback and support trends
- **Release Manager** tracks deployment frequency and success rates
- **Security Lead** monitors security metrics and vulnerability remediation

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: **Project Manager** escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Design blockers: Escalate to **UX Designer** for resolution
- Security concerns: Immediately involve **Security Lead**
- Customer-impacting issues: Notify **Support Lead** for impact assessment

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Security scanning integrated (**Security Lead** configured)
- [ ] Analytics instrumentation planned (**Data Analyst** specified requirements)
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly (**Project Manager** with **Security Lead**)
- [ ] Design reviews scheduled (**UX Designer** participates)
- [ ] Support team briefed on upcoming features (**Support Lead** engaged)
