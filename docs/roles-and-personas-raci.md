# OctoAcme — Roles & Responsibilities (RACI Matrix)

## Purpose
This matrix makes accountability explicit for core project activities. Use it to identify who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for each activity.

- **R — Responsible**: Does the work
- **A — Accountable**: Owns the outcome; final decision-maker (only one per row)
- **C — Consulted**: Provides input before or during the activity
- **I — Informed**: Notified of progress or completion

---

## RACI Table

| Activity                    | PM  | PdM | Developer | QA Lead | Scrum Master | UX Designer | Stakeholder | Sponsor |
|-----------------------------|-----|-----|-----------|---------|--------------|-------------|-------------|---------|
| One-pager / Project Charter  | R   | C   | I         | I       | I            | I           | C           | A       |
| Backlog Prioritization       | C   | A/R | C         | C       | C            | C           | C           | I       |
| Sprint Planning              | C   | C   | R         | C       | A/R          | C           | I           | I       |
| PR Review & Merge            | I   | C   | A/R       | C       | I            | C           | —           | —       |
| QA Sign-off                  | C   | C   | C         | A/R     | I            | I           | I           | I       |
| Release Approval (Minor)     | A   | C   | I         | R       | I            | I           | I           | I       |
| Release Approval (Major)     | C   | C   | I         | R       | I            | I           | I           | A       |
| Incident Response            | A   | C   | R         | C       | I            | —           | I           | I       |
| Retrospective Action Items   | C   | C   | R         | C       | A/R          | C           | I           | I       |

> **Note**: `A/R` means the same person is both Accountable and Responsible. `—` means the role is not typically involved.

---

## How to Use This Matrix

1. **Before a new activity begins**, confirm who holds each RACI role. Update the matrix if team composition has changed.
2. **When onboarding a new team member**, share this matrix alongside `role-onboarding-checklist.md` so they understand their accountabilities.
3. **When a role is vacant or in transition**, use this matrix to identify coverage gaps and assign interim owners.
4. **Review this matrix at the end of each major milestone** (or at minimum once per quarter) to ensure it reflects the current team structure.
5. **Add rows** for new recurring activities that emerge during the project (e.g., security review, architecture review board sign-off).

---

## Keeping the Matrix Current

- The PM owns the master copy of this matrix.
- Changes to the matrix should be proposed via PR and reviewed by the PM and PdM.
- Any change in team structure or role assignment that affects accountability should trigger an update within one sprint.
