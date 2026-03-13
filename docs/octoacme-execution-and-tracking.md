# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone
- **Scrum Master responsibilities in team rhythm:**
  - Facilitates all agile ceremonies (standup, planning, review, retrospective)
  - Tracks and shares sprint metrics (velocity, burndown) after each ceremony
  - Surfaces blockers in standup and escalates unresolved ones to PM within 24 hours
  - Coordinates backlog refinement with PdM before each sprint planning session
  - Reviews the board daily to flag stale or mis-categorized items

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
- **PR Readiness Checklist** (complete before requesting review):
  - [ ] Linked issue included in PR description
  - [ ] Acceptance criteria clearly stated or referenced
  - [ ] All automated tests passing in CI
  - [ ] Linting and security scans passing
  - [ ] QA steps or manual verification instructions listed in PR description
  - [ ] QA Lead assigned as reviewer if feature requires manual QA sign-off
  - [ ] Breaking changes or migration steps documented

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- **QA Lead responsibilities:**
  - Maintains the test strategy and test plans aligned to the current sprint
  - Provides test coverage report at the end of each sprint (shared with PM and PdM)
  - Owns the QA column on the project board — moves items to Done only after sign-off
  - Confirms QA hand-off steps are complete before the release cut (see `octoacme-release-and-deployment.md`)
  - Triages and tracks defects to resolution; escalates blocking defects to PM

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
