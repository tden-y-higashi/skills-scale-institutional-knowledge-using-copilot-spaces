# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a customer-first, iterative project management approach focused on clear ownership, data-informed decisions, and psychological safety. This documentation suite provides comprehensive guidance for running projects across the OctoAcme organization.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a structured lifecycle with clear phases, communication cadences, and decision gates:

1. **Initiation** - Define the problem, stakeholders, and business case
2. **Planning** - Break work into shippable increments and align timelines
3. **Execution & Tracking** - Manage day-to-day delivery and track progress
4. **Release & Deployment** - Standardize how features are released to production
5. **Retrospective & Continuous Improvement** - Capture learnings and improve processes

Throughout all phases, teams manage risks, maintain stakeholder communication, and follow established quality and testing standards.

## Key Project Management Processes

### Communication & Rhythm
- **Daily standups** (15 min) - Focus on progress, blockers, and dependencies
- **Weekly PM sync** - PM and Product Manager alignment
- **Twice-weekly delivery standups** - Team coordination
- **Weekly stakeholder updates** - Progress and risk reporting
- **Monthly stakeholder updates** - High-level status and metrics
- **Sprint/Milestone demos** - Feature review and feedback

### Quality & Execution Standards
- Small Pull Requests (≤ 400 lines when possible)
- Automated testing in CI (unit, integration, end-to-end)
- Security scanning and linting
- Code review with at least one approval
- Manual QA when needed for feature acceptance
- Project board tracking (Backlog, Ready, In Progress, In Review, QA, Done)

### Risk & Dependency Management
- Risk register maintained and updated weekly
- Three-level escalation: Team → PM → Product Lead → Sponsor
- Cross-team dependencies marked on project board
- Weekly risk reviews in sync meetings

### Success Metrics & Reporting
- Velocity and burndown tracking
- Success metrics defined in Project One-pager
- Dashboard monitoring for key signals (errors, latency, usage)
- Regular retrospectives to capture learnings and identify improvements

## Documentation Hub

### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md) - Introduction to OctoAcme's approach, core roles, and key artifacts
- [Roles and Personas](./octoacme-roles-and-personas.md) - Define responsibilities for Developers, Product Managers, and Project Managers

### Project Phases

#### Initiation
- [Project Initiation Guide](./octoacme-project-initiation.md) - Steps to validate work, align stakeholders, create lightweight plans, and reach go/no-go decision

#### Planning
- [Project Planning](./octoacme-project-planning.md) - Turn approved initiatives into actionable plans, backlogs, and milestone maps

#### Execution
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Manage day-to-day execution, quality standards, team rhythm, reporting, and blocker escalation

#### Release
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Standardized process for releasing features to production, including pre-release requirements and rollback procedures

#### Retrospectives & Improvement
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Structure retrospectives, capture learnings, track action items, and drive process improvements

### Cross-Cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Identify, manage, and communicate risks and dependencies throughout the project lifecycle; escalation paths and communication templates

## How to Use These Docs

- **For new team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) and [Roles and Personas](./octoacme-roles-and-personas.md) for context
- **When starting a project**: Follow the [Initiation Guide](./octoacme-project-initiation.md) and [Planning Guide](./octoacme-project-planning.md)
- **During execution**: Reference [Execution & Tracking](./octoacme-execution-and-tracking.md), [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **At milestones and releases**: Use [Release & Deployment Guide](./octoacme-release-and-deployment.md) and [Retrospective Guide](./octoacme-retrospective-and-continuous-improvement.md)
- **For Copilot Spaces**: Add process-specific docs to `.copilot/` to ground Copilot in your project's methodology

## Key Artifacts to Maintain

Every OctoAcme project should maintain:
- **Project Charter / One-pager** - Problem statement, objectives, success metrics, stakeholders, timeline
- **Roadmap and Release Plan** - Milestones and delivery schedule
- **Sprint/Iteration Backlog** - Prioritized work items with acceptance criteria
- **Definition of Done** - Quality standards and completion criteria
- **Risk Register** - Active risks, likelihood, impact, and mitigation
- **Retrospective notes** - Learnings and action items

---

*Last updated: 2026-10-08*  
*For questions or updates to these processes, please create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.*
