# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA (Quality Assurance)

### Role Summary
QA Engineers validate that features meet acceptance criteria and quality standards. They coordinate manual and automated testing across sprints and releases.

### Responsibilities
- Design and execute test plans based on acceptance criteria
- Run regression, integration, and smoke tests
- Report defects and track resolution
- Collaborate with developers on test coverage
- Provide sign-off before releases

### Goals
- Ensure high-quality, defect-free releases
- Maintain comprehensive test coverage
- Reduce post-release incidents

### Typical Communication
- QA status updates in standups and sprint reviews
- Defect reports and test result summaries
- Sign-off confirmation before release

---

## Stakeholder

### Role Summary
Stakeholders are individuals or groups with a direct interest in the project's outcomes. They provide input on business requirements, validate deliverables, and champion the project within their domain.

### Responsibilities
- Review deliverables and provide timely feedback
- Communicate requirements and business constraints to PM and PdM
- Escalate risks or gaps to the PM or Sponsor
- Participate in demos and milestone reviews
- Advocate for the project within their organization

### Goals
- Ensure delivered outcomes meet business needs
- Maintain visibility into project progress and risks
- Represent the interests of end users and the business

### Typical Communication
- Attendance at sprint demos and milestone reviews
- Async feedback via issue comments or review documents
- Escalation conversations with PM and Sponsor

### Interactions
- **with PM**: Primary day-to-day contact; receives status updates and flags risks
- **with PdM**: Provides business requirements and validates product direction
- **with Developers**: Reviews demos; rarely interacts directly outside review sessions
- **with QA**: Reviews acceptance criteria; may participate in UAT
- **with Sponsor**: Escalates critical risks; receives executive summaries

---

## Sponsor

### Role Summary
The Sponsor is the executive champion with the authority to approve resources, remove organizational roadblocks, and make final decisions on scope or budget changes.

### Responsibilities
- Approve funding, scope changes, and major milestones
- Resolve escalated issues that the PM cannot unblock
- Ensure the project stays aligned with business objectives
- Receive and act on regular high-level status updates
- Provide final approval for Major releases

### Goals
- Protect the business value of the project
- Remove organizational impediments quickly
- Ensure executive visibility into project health

### Typical Communication
- Monthly or milestone-based executive briefings from PM
- Escalation calls when critical risks materialize
- Approval sign-off for Major releases and budget changes

### Interactions
- **with PM**: Receives regular status reports; escalation path for critical blockers
- **with PdM**: Aligns on product strategy and major scope decisions
- **with Stakeholders**: Receives escalated concerns; provides direction
- **with Developers**: Indirect; aware of major technical risks through PM
- **with QA**: Final approver for Major release sign-off with QA Lead confirmation

---

## UX Designer

### Role Summary
UX Designers create user experiences and interfaces that are usable, accessible, and aligned with product goals. They translate requirements into wireframes, prototypes, and design specifications.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity design flows
- Maintain a design system and component library
- Collaborate with PdM on feature requirements and acceptance criteria
- Review implemented features for design fidelity

### Goals
- Deliver intuitive, accessible user experiences
- Ensure design decisions are grounded in user research
- Reduce rework by aligning on designs before development begins

### Typical Communication
- Design reviews with PdM and Developers at the start of each feature
- Usability test findings shared with PM, PdM, and team
- Async feedback via design tool comments or PR reviews

### Interactions
- **with PM**: Flags design-related risks or timeline impacts
- **with PdM**: Primary collaboration partner for feature scoping and acceptance criteria
- **with Developers**: Handoff of design specs; available for implementation questions
- **with QA**: Shares design specs so QA can validate visual and interaction fidelity
- **with Stakeholders**: Presents prototypes for feedback during discovery

---

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, removes impediments, and coaches the team on continuous improvement. They protect the team's focus and help maintain a healthy delivery cadence.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint review, and retrospectives
- Identify and remove blockers that impede team progress
- Coach team members on Agile principles and practices
- Track and report sprint metrics (velocity, burndown)
- Coordinate with PM and PdM to keep the backlog ready and refined

### Goals
- Maintain a predictable, sustainable delivery pace
- Continuously improve team processes and collaboration
- Minimize the time blockers remain unresolved

### Typical Communication
- Daily standup facilitation
- Blocker escalation to PM or Sponsor when needed
- Sprint reports and retrospective action items shared with the team

### Interactions
- **with PM**: Escalates unresolved blockers; shares sprint health metrics
- **with PdM**: Ensures backlog refinement happens before sprint planning
- **with Developers**: Day-to-day facilitation; shields from outside interruptions
- **with QA**: Coordinates QA capacity planning within sprints
- **with Stakeholders**: Facilitates demo sessions; manages feedback during reviews

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for the project, coordinates the QA team or effort, and provides the final quality sign-off before releases. They bridge the gap between development completion and production deployment.

### Responsibilities
- Define and maintain the test strategy and test plans
- Lead manual and automated testing efforts across sprints
- Report on test coverage, defect trends, and quality metrics
- Provide formal sign-off for releases (Minor and Major)
- Coordinate with Developers on defect triage and resolution
- Ensure QA hand-off steps are completed before release cut

### Goals
- Prevent defect leakage to production
- Maintain high test coverage across critical paths
- Provide clear, data-backed quality gates for release decisions

### Typical Communication
- QA status in sprint reviews and release readiness meetings
- Formal written sign-off confirmation shared with PM and Sponsor
- Defect triage sessions with Developers

### Interactions
- **with PM**: Provides release readiness assessment; escalates blocking defects
- **with PdM**: Validates acceptance criteria coverage in test plans
- **with Developers**: Primary collaboration for defect resolution and coverage
- **with QA**: Leads and mentors QA team; coordinates testing assignments
- **with Sponsor**: Provides quality summary for Major release approvals

---

## Role Interaction Example Scenario

**Scenario: Feature Handoff and Release Escalation**

During sprint planning, the UX Designer hands off finalized designs to the Developers, ensuring specs are available before work begins. Mid-sprint, the Scrum Master flags in standup that a dependent API from another team is delayed, creating a potential blocker. The PM escalates this dependency to the Sponsor, who unblocks it with a same-day conversation with the other team's director.

As the sprint closes, the QA Lead runs the test plan, identifies a critical defect, and reports it to the PM. The PM and PdM decide to hold the release until the defect is fixed. Once resolved, the QA Lead provides written sign-off. For a Major release, the PM notifies the Sponsor and Stakeholders, who confirm alignment before the PM approves the deployment.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-reference with `roles-and-personas-raci.md` for accountability mapping across activities.

