# OctoAcme Project Management Docs

This README provides a short summary of OctoAcme's project management processes and direct links to the process documents stored in the docs/ folder.

## Summary

OctoAcme follows a structured, lifecycle-based approach to project management that spans five core phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. The methodology is grounded in customer-first principles, iterative delivery, and clear ownership.

During **Initiation**, teams validate business need and create a lightweight Project One-pager that defines the problem statement, measurable success metrics, stakeholders, and initial timeline. Once stakeholders align and the go/no-go decision is made, the project moves into **Planning**, where work is broken into shippable increments, dependencies are mapped, and a prioritized backlog with acceptance criteria is established.

**Execution and Tracking** are synchronized through a consistent team rhythm: daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations managed on a project board. Pull requests are kept small (≤400 lines when possible) with issue links and acceptance criteria, and require at least one approval before merging. Quality is embedded throughout via unit tests, integration tests, smoke tests, and security scanning in CI. Teams measure velocity, burndown, and success metrics to stay data-informed, with three-level escalation paths for blockers.

OctoAcme operates with clear **roles and responsibilities**: **Product Managers** define what should be built and prioritize the backlog; **Project Managers** coordinate delivery, manage risks, and facilitate communications; **Developers** implement features and collaborate on design and testability; and **Stakeholders** provide inputs and approvals. **Risk Management** is continuous, with a maintained Risk Register tracking ID, description, impact, likelihood, owner, and mitigation plans.

At **Release**, teams ensure all acceptance criteria are met, CI and security scans pass, release notes are drafted, and a rollback plan is documented before deploying to production. After each sprint, release, or milestone, teams conduct **Retrospectives** to capture learnings and convert insights into 2–3 prioritized action items with clear owners and due dates. This continuous improvement cycle enables OctoAcme teams to deliver reliably and reduce single-person dependency risk.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, roles, artifacts, and lifecycle
- [Project Initiation Guide](./octoacme-project-initiation.md) — Steps to validate, authorize, and plan new work
- [Project Planning](./octoacme-project-planning.md) — How to break work into shippable increments and create backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, standups, PR workflow, and quality practices
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, and rollback procedures
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk register maintenance, stakeholder communication, and escalation paths
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — How to capture learnings and convert them into action items
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed responsibilities for Developers, Product Managers, and Project Managers

## How to Contribute

If you'd like to propose changes or add a new process doc, open an issue using the **"Add Content to Project Management Process Docs"** template and include:
- A summary of the new content or update
- Rationale for the change
- Suggested content (optional)

Your contribution will be reviewed to ensure alignment with existing processes and overall improvement to the documentation.
