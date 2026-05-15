---
name: "Add OctoAcme Project Management Docs README"
description: "Create a comprehensive README for OctoAcme Project Management Docs with links to all process documents and summary"
title: "[Process Doc Update]: Add README for OctoAcme Project Management Docs with process summary and links"
labels: ["documentation", "process improvement"]
---

## Process Document: New Document (README for OctoAcme Docs)

## Summary of New Content
Create a comprehensive README file for the OctoAcme Project Management Docs that:
- Provides an overview of the OctoAcme project management framework
- Includes links to all process documentation files in the docs/ folder
- Summarizes the key project management processes and lifecycle stages
- Explains how to use these documents as a knowledge base

## Why is this update needed?
Currently, team members navigating the docs/ folder lack a central entry point to understand the complete project management framework. A README will:
- Improve discoverability of all process documents
- Provide quick context for new team members and contributors
- Establish a single source of truth for OctoAcme processes
- Make it easier to understand how all documents connect together

## Suggested Content

### Proposed README.md for docs/ folder:

```markdown
# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation suite. This knowledge base contains standardized processes, templates, and guidance for running projects at OctoAcme.

## Quick Start

New to OctoAcme projects? Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our approach, core roles, and key artifacts.

## Project Lifecycle & Processes

Our project management framework follows five key phases:

### 1. **Initiation** — Validate & Authorize Work
→ [Project Initiation Guide](octoacme-project-initiation.md)
- Confirm business need and measurable outcomes
- Identify stakeholders and champions
- Define success criteria and initial timeline
- Create a lightweight Project One-pager

### 2. **Planning** — Create Actionable Plan
→ [Project Planning](octoacme-project-planning.md)
- Break work into shippable increments
- Identify dependencies and risks
- Align timelines, releases, and responsibilities
- Create prioritized backlog with acceptance criteria

### 3. **Execution & Tracking** — Day-to-Day Delivery
→ [Execution & Tracking](octoacme-execution-and-tracking.md)
- Manage via project board (GitHub Projects)
- Follow pull request and code review workflow
- Track velocity and burndown
- Escalate blockers through defined levels

### 4. **Release & Deployment** — Move to Production
→ [Release & Deployment Guide](octoacme-release-and-deployment.md)
- Standardize release types (patch, minor, major)
- Meet pre-release requirements and checklists
- Execute deployment safely with rollback plans
- Verify and announce releases

### 5. **Close & Continuous Improvement** — Capture Learnings
→ [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- Run retrospectives after sprints, releases, or milestones
- Document action items and track improvements
- Build a continuous improvement culture

## Cross-Cutting Concerns

### Roles & Personas
→ [OctoAcme Roles & Personas](octoacme-roles-and-personas.md)

Learn about the core roles in OctoAcme projects:
- **Developers** — Design, build, test, and deliver software
- **Product Managers** — Define what to build and measure outcomes
- **Project Managers** — Coordinate delivery, manage risks and communications

### Risk Management & Communication
→ [Risk Management & Communication](octoacme-risks-and-communication.md)

- Maintain and monitor a risk register throughout project lifecycle
- Use escalation paths for stakeholder communication
- Provide consistent status updates using standard templates

## Core Principles

- **Customer-first** — Prioritize customer value and usability
- **Iterative delivery** — Deliver small, testable increments
- **Clear ownership** — Named Project Manager and Product Lead for each project
- **Data-informed decisions** — Measure impact and iterate based on evidence
- **Psychological safety** — Encourage feedback and learning

## Key Artifacts You'll Create

Across the project lifecycle, you'll maintain:
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Getting Started

1. **For a new project:** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
2. **For planning & execution:** Use [Project Planning](octoacme-project-planning.md) and [Execution & Tracking](octoacme-execution-and-tracking.md)
3. **For releases:** Reference the [Release & Deployment Guide](octoacme-release-and-deployment.md)
4. **After milestones:** Schedule a [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Using These Docs in Copilot Spaces

These documents can be added to a Copilot Space to provide context-specific guidance. When adding to a Space:
- Include all files from the `docs/` folder to ground Copilot in OctoAcme processes
- Reference specific documents when seeking role-specific guidance
- Use the templates and checklists as starting points for your project artifacts

## Document Index

| Document | Purpose |
|----------|---------|
| [octoacme-project-management-overview.md](octoacme-project-management-overview.md) | Introduction to OctoAcme approach, roles, and artifacts |
| [octoacme-project-initiation.md](octoacme-project-initiation.md) | Steps to validate and authorize new work |
| [octoacme-project-planning.md](octoacme-project-planning.md) | How to create actionable plans and backlogs |
| [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) | Day-to-day delivery and progress tracking |
| [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) | Risk management and stakeholder communication |
| [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) | Release planning and deployment procedures |
| [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) | Retrospectives and capturing learnings |
| [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) | Role definitions and responsibilities |

---

**Questions?** Refer to the relevant process document or open an issue for process improvements using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
```

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [x] Proposed content has been reviewed with stakeholders (if needed)
