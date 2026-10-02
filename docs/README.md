# OctoAcme Project Management Documentation

## Overview

OctoAcme uses a structured, iterative project management approach focused on customer value, clear ownership, and data-informed decisions. Our methodology emphasizes psychological safety, transparent communication, and continuous improvement.

### Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leadership
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow five key phases:

1. **Initiation** – Define the business need, align stakeholders, and create a lightweight project charter with success metrics and an initial timeline
2. **Planning** – Break work into shippable increments, estimate scope, define acceptance criteria and Definition of Done, and identify dependencies
3. **Execution** – Build and test features through daily standups, weekly delivery syncs, and iterative reviews while maintaining quality standards
4. **Release** – Deploy to production using pre-release checklists, smoke tests, and rollback plans, then communicate changes to stakeholders
5. **Close & Retrospective** – Capture lessons learned, turn action items into backlog work, and measure the impact of process improvements

## How OctoAcme Delivers Quality

Quality is built into every stage of delivery:

- **During development**: unit tests, code review, PR requirements, and automated CI checks before merge
- **Before release**: acceptance criteria validation, security scans, smoke tests, and documented rollback plans
- **After release**: post-deployment verification, incident response playbooks, and blameless retrospectives

Communication follows a predictable rhythm: daily standups for progress and blockers, weekly syncs between PM and Product Lead, twice-weekly delivery team standups, and monthly stakeholder updates. Risks are identified during planning, tracked in a risk register, and escalated through clear ownership paths: team triage → PM → Product Lead → Sponsor.

## Process Documentation

### Foundational Guides

- [**Project Management Overview**](octoacme-project-management-overview.md) – introduction to OctoAcme’s approach, core roles, key artifacts, and lifecycle
- [**Roles & Personas**](octoacme-roles-and-personas.md) – responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers

### By Project Phase

- [**Project Initiation**](octoacme-project-initiation.md) – validate business need, identify stakeholders, create a one-pager, and decide whether to proceed
- [**Project Planning**](octoacme-project-planning.md) – break work into prioritized increments, estimate scope, define Definition of Done, and plan milestones
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) – manage day-to-day delivery, use project boards, and track progress, metrics, and blockers
- [**Release & Deployment**](octoacme-release-and-deployment.md) – standardize releases, prepare checklists, reduce risk, and handle deployment or incident recovery

### Cross-Cutting Disciplines

- [**Risk Management & Communication**](octoacme-risks-and-communication.md) – identify, assess, and mitigate risks; maintain a register; communicate status and escalate issues
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) – run effective retrospectives, capture action items, and build a learning culture

## Quick Navigation by Role

### For Developers

Start here to understand how to execute high-quality work:

1. [Roles & Personas](octoacme-roles-and-personas.md)
2. [Execution & Tracking](octoacme-execution-and-tracking.md)
3. [Release & Deployment](octoacme-release-and-deployment.md)

### For Product Managers

Start here to define and prioritize the work:

1. [Project Management Overview](octoacme-project-management-overview.md)
2. [Project Initiation](octoacme-project-initiation.md)
3. [Project Planning](octoacme-project-planning.md)
4. [Risk Management & Communication](octoacme-risks-and-communication.md)

### For Project Managers

Start here to coordinate and manage delivery:

1. [Project Management Overview](octoacme-project-management-overview.md)
2. [Project Planning](octoacme-project-planning.md)
3. [Execution & Tracking](octoacme-execution-and-tracking.md)
4. [Risk Management & Communication](octoacme-risks-and-communication.md)
5. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Using These Docs

- **New team members**: start with [Project Management Overview](octoacme-project-management-overview.md), then follow the role-specific guide above
- **Starting a new project**: follow the lifecycle in order: Initiation → Planning → Execution → Release
- **Process improvement**: use the issue template in [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates
- **Copilot Spaces**: these docs are intended to be used as contextual project knowledge for team guidance and onboarding

## Contributing to OctoAcme Processes

Help improve the team’s project management practices by proposing updates, clarifying missing details, or suggesting new process guidance. Use the issue template in [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml), describe the gap, and collaborate with the team on the best path forward.
