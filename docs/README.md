# OctoAcme Project Management Docs

Welcome! This README provides an overview and entry point to all OctoAcme project management process documentation.

## Overview of OctoAcme Project Management Processes

### Structured Lifecycle & Iterative Approach

OctoAcme employs a structured yet iterative project management approach designed around customer value delivery and psychological safety. The process spans five key phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (building, testing, and iterating with daily oversight), **Release** (deploying to production with standardized checklists and rollback procedures), and **Close & Retrospective** (capturing learnings and continuous improvement). This lifecycle emphasizes data-informed decisions, small testable increments, and clear ownership, ensuring that all cross-functional projects delivering product features, services, or integrations maintain consistency and traceability from conception through closure.

### Core Roles & Communication Cadence

OctoAcme defines three primary personas—**Developers**, **Product Managers**, and **Project Managers**—each with distinct responsibilities that work in concert. Developers implement features to acceptance criteria while maintaining high code quality and test coverage; Product Managers define what should be built by prioritizing the backlog and measuring outcomes; and Project Managers coordinate schedules, risks, and communications to ensure on-time delivery. Communication is formalized through a weekly sync between the PM and Product Manager, twice-weekly standups for the delivery team, and monthly stakeholder updates, with ad-hoc escalations for risks that move from team-level triage → PM → Product Lead → Sponsor when needed. This structured cadence combined with named ownership creates transparency and reduces single-person dependency risk.

### Quality Assurance & Execution Discipline

Execution relies on GitHub Projects for workflow visibility (Backlog → Ready → In Progress → In Review → QA → Done), small pull requests (≤400 lines), mandatory automated testing and linting in CI, and at least one approval before merging. Quality gates include unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. The team tracks velocity, burndown, and success metrics against a documented Definition of Done, with manual QA for feature acceptance as needed. Pre-release requirements are rigorous—all acceptance criteria must be met, security scans passed, and rollback plans documented—positioning the team to deploy with confidence and observability.

### Risk Management & Continuous Improvement

OctoAcme maintains a **Risk Register** (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) that is reviewed and updated at weekly syncs, ensuring risks are identified during planning, assessed, mitigated through concrete actions, and monitored throughout delivery. Stakeholder communication is centralized in a single source of truth (project README or release notes), with templates for weekly status updates and incident communication to keep all parties informed. After each sprint, release, or milestone, the team holds a **Retrospective** (45–75 minutes) to capture what went well, what could improve, and prioritize 2–3 actionable items for the backlog. This embedded culture of blameless retrospectives and measured continuous improvement ensures that OctoAcme projects not only deliver on their current commitments but systematically strengthen delivery capabilities over time.

---

## Core Principles

- **Customer-first**: Focus on delivering customer value and usability
- **Iterative delivery**: Work in small, testable increments
- **Clear ownership**: Every project has a Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Transparent collaboration**: Regular updates and clear escalation paths

## Project Lifecycle Stages

1. **Initiation** — Problem, stakeholders, metrics, initial plan  
   [→ Initiation Guide](./octoacme-project-initiation.md)

2. **Planning** — Scope, backlog, risks, release plan  
   [→ Planning Guide](./octoacme-project-planning.md)

3. **Execution & Tracking** — Standups, sprints, reviews, QA, metrics  
   [→ Execution & Tracking](./octoacme-execution-and-tracking.md)

4. **Risk Management & Communication** — Risk register, communication templates  
   [→ Risks & Communication](./octoacme-risks-and-communication.md)

5. **Release & Deployment** — Release types, checklists, rollback  
   [→ Release & Deployment](./octoacme-release-and-deployment.md)

6. **Retrospectives & Continuous Improvement** — Capture lessons, action items  
   [→ Retrospective Guide](./octoacme-retrospective-and-continuous-improvement.md)

## Additional Reference Docs

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts
- [Roles and Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of Developers, Product Managers, and Project Managers

---

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) and [Roles and Personas](./octoacme-roles-and-personas.md) to understand the framework.
- **Starting a new project?** Follow the lifecycle stages in order, beginning with [Initiation Guide](./octoacme-project-initiation.md).
- **In the middle of execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md) for day-to-day guidance.
- **Preparing for release?** Review [Release & Deployment](./octoacme-release-and-deployment.md).
- **Wrapping up?** Use [Retrospective Guide](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings.

For updates or additions to these docs, use the [Process Doc Update Issue Template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
