# OctoAcme Project Management Docs — README

Welcome! This README provides an at-a-glance introduction to OctoAcme's project management approach and links to all key process documents.

## OctoAcme Project Management Overview

OctoAcme operates a structured, customer-centric project management approach designed for cross-functional teams delivering product features and services. The methodology is built on five core principles: prioritizing customer value and usability, embracing iterative delivery through small testable increments, establishing clear ownership with named Project Managers (PMs) and Product Leads, making data-informed decisions, and fostering psychological safety.

### Key Workflows & Execution Model

Execution follows a predictable rhythm with **daily standups** (15 minutes focused on progress and blockers), **weekly syncs** between PM and Product Lead, **twice-weekly delivery team standups**, and **monthly stakeholder updates**. Work is tracked using GitHub Projects with columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforced through small pull requests (≤400 lines) with automated CI testing, linting, and at least one approval before merging.

### Quality Assurance & Risk Management

OctoAcme maintains rigorous quality standards through unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release, with security scanning integrated into CI pipelines. Risk management follows a tiered escalation model (Level 1: team standup triage, Level 2: PM escalation to Product Lead, Level 3: sponsor escalation). The organization maintains a formal Risk Register reviewed at weekly syncs and conducts retrospectives after each sprint or milestone to capture learnings and drive continuous improvement.

### Roles & Personas

Three primary personas drive delivery:
- **Product Managers** define what should be built, prioritize the backlog, and measure outcomes
- **Project Managers** coordinate delivery, manage schedules, risks, and stakeholder communication
- **Developers** design, build, test, and deliver features while collaborating on design and quality standards

### Release & Communication Strategy

Before any release, the team ensures all acceptance criteria are met, CI and security scans pass, release notes are drafted, and rollback plans are documented. Deployment follows a phased approach: staging validation, production deployment (preferably automated), post-deploy verification, and stakeholder announcement. Communication uses consistent weekly status templates and incident protocols with blameless retrospectives.

---

## Process Document Links

Navigate the full project lifecycle using these process documents:

| Phase | Document | Purpose |
|-------|----------|---------|
| **Overview** | [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, roles, and key artifacts |
| **Initiation** | [Project Initiation Guide](octoacme-project-initiation.md) | Initial steps to validate, authorize, and plan new work |
| **Planning** | [Project Planning](octoacme-project-planning.md) | Turn approved initiatives into actionable plans and prioritized backlogs |
| **Execution** | [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution, team rhythm, and progress tracking |
| **Risk & Comms** | [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| **Release** | [Release & Deployment](octoacme-release-and-deployment.md) | Standardized release and deployment procedures |
| **Retrospective** | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| **Roles** | [Roles & Personas](octoacme-roles-and-personas.md) | Detailed definitions of typical roles and responsibilities |

---

## Getting Started

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction.
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md).
- **Need to plan work?** Use [Project Planning](octoacme-project-planning.md) to structure your backlog and timeline.
- **Managing ongoing work?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md).
- **Releasing to production?** Follow [Release & Deployment](octoacme-release-and-deployment.md) procedures.

---

## Contributing

All docs are in the [`docs/`](.) directory. Contributions to improve clarity, add missing processes, or refine existing guidance are welcome! 

To propose updates:
1. Create an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Reference the specific document and describe your suggested changes
3. Include rationale and any example content
4. Submit a pull request with the updated document

---

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning
