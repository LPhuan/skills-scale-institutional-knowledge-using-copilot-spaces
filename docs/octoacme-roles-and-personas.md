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

## QA / Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy, test planning, and acceptance validation. They collaborate with developers and product managers to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define and maintain test strategy and test plans for each release
- Create and execute test cases, both manual and automated
- Validate acceptance criteria before marking work as complete
- Identify and triage quality issues, coordinate with developers on fixes
- Participate in sprint planning to estimate testing effort
- Maintain test infrastructure and automation frameworks

### Goals
- Ensure all features meet quality standards and acceptance criteria
- Reduce defects in production through comprehensive testing
- Enable fast, confident releases with clear quality gates

### Typical Communication
- Sprint planning and daily standups
- Quality review meetings with product and engineering leads
- Test plan and bug report documentation
- QA status updates in weekly syncs

### Interaction with other roles
- Works with **Developers** to understand implementation details and provide early feedback on testability
- Collaborates with **Product Managers** to validate that features meet acceptance criteria and business requirements
- Partners with **Project Managers** to flag quality risks and ensure testing timelines are reflected in project schedules
- Works alongside **Technical Leads** to design comprehensive test strategies that cover technical complexity
- Coordinates with **Security/Compliance Officers** to ensure security and compliance testing is included

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide technical decisions, conduct design reviews, and help identify and mitigate technical risks. They work closely with developers and project managers to ensure solutions are scalable, maintainable, and aligned with system architecture.

### Responsibilities
- Lead technical design discussions and architecture reviews
- Provide guidance on technology choices and trade-offs
- Identify technical risks and propose mitigation strategies
- Mentor developers and review designs for quality and maintainability
- Ensure solutions align with system architecture and long-term vision
- Participate in sprint planning to identify technical complexity

### Goals
- Deliver technically sound, scalable, and maintainable solutions
- Reduce technical debt and architectural misalignment
- Enable team velocity through clear technical direction

### Typical Communication
- Design review meetings and architecture discussions
- Technical documentation and ADRs (Architecture Decision Records)
- Code reviews and technical feedback
- Sprint planning and risk assessment discussions

### Interaction with other roles
- Mentors and guides **Developers** on technical approach and best practices
- Partners with **Product Managers** to assess technical feasibility and timeline impact of features
- Works with **Project Managers** to flag technical dependencies and risks that affect delivery schedules
- Collaborates with **QA/Testing Leads** to design testable architectures and identify edge cases
- Engages with **Scrum Masters** to remove technical blockers and facilitate design discussions

---

## Stakeholder / Business Owner

### Role Summary
Stakeholders and Business Owners provide business context, approval authority, and success criteria alignment. They represent customer interests, business priorities, and organizational constraints in project decisions.

### Responsibilities
- Define business objectives and success criteria
- Provide approval authority for scope and priority decisions
- Communicate business constraints and opportunities
- Validate that solutions address the stated business need
- Represent customer or organizational interests in trade-off discussions
- Participate in milestone reviews and release approvals

### Goals
- Ensure projects deliver measurable business value
- Align project outcomes with organizational strategy
- Maximize stakeholder satisfaction and ROI

### Typical Communication
- Milestone reviews and project kickoffs
- Monthly status updates and decision gates
- Stakeholder briefings and risk escalations
- Release announcements and impact reviews

### Interaction with other roles
- Works with **Product Managers** to define business requirements and success metrics
- Partners with **Project Managers** to approve timelines, scope changes, and resource needs
- Engages with **Developers** during design reviews to validate business feasibility
- Provides input to **QA/Testing Leads** on business-critical acceptance criteria
- Receives risk escalations from **Technical Leads** on business-impacting technical decisions

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team ceremonies, remove blockers, and coach the team on agile practices. They enable self-organizing teams to deliver value consistently and improve over time.

### Responsibilities
- Facilitate sprint planning, standup, review, and retrospective meetings
- Remove impediments and blockers that prevent team progress
- Coach the team on agile practices and continuous improvement
- Maintain sprint board and tracking artifacts
- Escalate risks and dependencies to Project Manager
- Foster psychological safety and team collaboration

### Goals
- Enable consistent, predictable team velocity
- Improve team collaboration and communication
- Drive continuous process improvement
- Remove obstacles to delivery

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment tracking and escalation
- Retrospective notes and improvement action items
- Coaching feedback and process guidance

### Interaction with other roles
- Works with **Project Managers** to track progress and escalate blockers
- Coaches **Developers** on agile principles, estimation, and technical collaboration
- Supports **Product Managers** in managing backlog refinement and sprint planning
- Partners with **QA/Testing Leads** to ensure testing is integrated into sprint planning
- Facilitates collaboration with **Technical Leads** to manage technical dependencies and design reviews
- Keeps **Stakeholders** informed of progress and impediments during sprint reviews

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that security requirements, compliance regulations, and risk management practices are embedded throughout the project lifecycle. They protect the organization and customers by validating that solutions meet security and compliance standards.

### Responsibilities
- Define security requirements and compliance standards for projects
- Conduct security and compliance reviews of designs and implementations
- Identify and assess security risks and vulnerabilities
- Recommend mitigation strategies and technical controls
- Coordinate security testing and vulnerability scans in CI
- Track compliance status and audit trail for regulatory requirements

### Goals
- Ensure projects meet security and compliance standards
- Reduce security incidents and compliance violations
- Enable secure, compliant delivery without compromising velocity
- Build security into the development process from the start

### Typical Communication
- Design security reviews and threat assessments
- Security testing reports and vulnerability findings
- Compliance checklists and audit documentation
- Risk escalations and mitigation planning

### Interaction with other roles
- Partners with **Developers** to embed security practices and review code for vulnerabilities
- Collaborates with **Product Managers** to incorporate security and compliance requirements into acceptance criteria
- Works with **Project Managers** to track security milestones and compliance checkpoints
- Engages with **Technical Leads** to design secure architectures and evaluate technology choices
- Partners with **QA/Testing Leads** to define security and compliance test scenarios
- Provides risk assessments to **Stakeholders** on security and compliance impacts

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand how personas interact to communicate effectively across your team and manage dependencies.
