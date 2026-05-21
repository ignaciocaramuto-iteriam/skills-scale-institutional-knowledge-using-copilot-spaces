# OctoAcme Project Management Docs

Welcome! This README provides an overview of how OctoAcme approaches project management and quick links to all of our current process documentation.

## OctoAcme Project Management Approach

OctoAcme follows a structured, lifecycle-based approach to project delivery that emphasizes customer value, iterative delivery, clear ownership, and data-informed decisions. Our framework spans five core phases—**Initiation, Planning, Execution, Release, and Close & Retrospective**—ensuring projects are well-scoped, aligned with stakeholders, and continuously improved.

### Key Principles
- **Customer-first:** Prioritize customer value and usability in all decisions
- **Iterative delivery:** Deliver small, testable increments regularly
- **Clear ownership:** Each project has a named Project Manager and Product Lead
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning across the team

### Core Roles & Responsibilities
- **Project Manager (PM):** Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes the backlog, and measures success
- **Developers:** Implement features, collaborate on design, and contribute to planning
- **QA/Testing:** Validates quality and acceptance criteria
- **Stakeholders:** Provide inputs, approvals, and strategic direction

### Team Rhythm & Communication
- **Daily standups** (15 min): Focus on progress, blockers, and dependencies
- **Weekly PM + PdM sync:** Alignment on priorities and risk management
- **Twice-weekly delivery standups:** Team-level coordination (or as agreed)
- **Monthly stakeholder updates:** High-level status and strategic alignment
- **Ad-hoc escalations:** Three-level path (team → PM → Product Lead → Sponsor)

### Execution & Quality Standards
- Small pull requests (≤400 lines when possible) with linked issues and acceptance criteria
- Automated CI/CD with tests, linting, and security scanning
- Unit tests, integration tests, and end-to-end smoke tests for critical flows
- Manual QA for feature acceptance when needed
- Clear Definition of Done documented during planning

### Key Artifacts
- Project Charter / One-pager
- Prioritized backlog with acceptance criteria
- Risk Register (ID, description, impact, likelihood, owner, mitigation)
- Release plan and milestone timeline
- Sprint/iteration backlog
- Retrospective notes and action items

### Continuous Improvement
After each sprint, release, or milestone, the team holds a **retrospective** (45–75 min) to capture what went well, what could improve, and to generate 2–3 prioritized action items. These action items feed back into the project backlog and are tracked in weekly PM syncs, creating a feedback loop that drives iterative process enhancements.

---

## Process Docs Index

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — Start here for a concise introduction to OctoAcme's approach, core roles, key artifacts, and lifecycle

### By Project Phase
1. **[Project Initiation Guide](octoacme-project-initiation.md)** — Validate business need, identify stakeholders, confirm success criteria, and decide go/no-go for planning
2. **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, estimate scope, identify dependencies, and create a release plan
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, team rhythm, quality standards, and blocker escalation
4. **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize release types, pre-release requirements, deployment checklist, and rollback procedures
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, convert them into actionable improvements, and track impact

### Cross-Cutting Topics
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify and manage risks, maintain a risk register, communicate with stakeholders, and escalate effectively
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of developer, product manager, and project manager responsibilities, goals, and communication patterns

---

## Quick Reference: Templates & Checklists

### Project One-pager Template
Used during **Initiation** to align stakeholders and confirm business need:
- Project name
- Problem statement
- Objective / Goal (SMART)
- Success metrics
- Primary stakeholders
- Suggested timeline / milestones
- Quick risks & dependencies
- Proposed team / roles

### Backlog Item Template
Used during **Planning** to define work:
- Title
- Description
- Acceptance criteria
- Priority
- Estimate
- Owner
- Related docs/links

### Weekly Status Template
Used during **Execution** to communicate progress:
- Progress this week
- Next steps
- Risks & blockers
- Ask / decisions needed

### Risk Register Template
Maintained throughout the project:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

---

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md), then navigate to the phase-specific doc for your current work.
- **Managing a project?** Use the phase-based docs as checklists and reference guides. Keep your Project Charter and Risk Register updated in your project repo.
- **Contributing to process docs?** Submit updates or new content using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
- **Want Copilot Spaces context?** Add process docs to `.copilot/` in your project repo to ground Copilot Space assistance in your team's workflows.

---

## Contributing to OctoAcme Process Docs

Our processes evolve as the team learns and grows. If you have feedback, gaps to address, or improvements to propose:

1. Open a new issue using the **[Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Describe the update, rationale, and suggested content
3. Engage stakeholders for review and feedback
4. Submit a pull request linking to the issue

---

*Last updated: May 2026*