# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks (PM and Product Manager coordinate)
- Demo/Review at the end of each sprint or milestone (include UX Designer for design validation)
- Regular design reviews between UX Designer and Developers
- Documentation reviews with Technical Writer aligned to release milestones

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (reviewed in PR process)
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release (coordinated with DevOps Engineer)
- Security scanning in CI (managed by DevOps Engineer)
- Manual QA for feature acceptance when needed
- Usability testing by UX Designer for key user flows
- Documentation review by Technical Writer before release

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates resolution)
- Level 2: PM escalates to Product Lead and dependent teams (Scrum Master may assist)
- Level 3: Sponsor-level escalation for business-impacting issues
- Infrastructure/deployment blockers: DevOps Engineer coordinates resolution
- Design blockers: UX Designer works with Product Manager to resolve

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
