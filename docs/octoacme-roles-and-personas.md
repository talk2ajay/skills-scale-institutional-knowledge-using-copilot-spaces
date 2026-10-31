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

## Security Engineers

### Role Summary
Security Engineers embed secure design and engineering practices into delivery. They help teams identify risks early, reduce security debt, and ensure security decisions align with business needs and risk tolerance.

### Responsibilities
- Review architecture and features for security risks, privacy concerns, and threat exposure
- Partner with product and engineering on secure design trade-offs and risk acceptance
- Define secure coding patterns, dependency hygiene, and validation requirements
- Support remediation planning and prioritization for vulnerabilities
- Participate in release readiness checks for high-risk changes

### Goals
- Reduce security risk across the product lifecycle
- Increase secure defaults and resilience in delivery
- Align security decisions with product, customer, and compliance needs

### Typical Communication
- Architecture and design reviews
- Sprint planning and risk reviews
- Security triage and incident response coordination
- Release readiness and deployment checks

### Interaction with Existing Roles
- Works with Developers to review implementation choices and secure design patterns
- Advises Product Managers and Project Managers on risk trade-offs, release gates, and compliance concerns
- Coordinates with Stakeholders when security exceptions or escalations are required
- Supports Engineering Managers / Tech Leads on prioritization and risk-based delivery planning

---

## Engineering Managers / Tech Leads

### Role Summary
Engineering Managers or Tech Leads guide delivery execution, team coordination, and technical prioritization. They connect product goals with engineering capacity and technical health.

### Responsibilities
- Coordinate delivery planning, staffing, and execution across teams
- Help resolve technical dependencies, bottlenecks, and cross-team coordination issues
- Support definition of technical direction, architecture decisions, and quality standards
- Partner with PMs and Product Managers on sequencing, scope trade-offs, and delivery risk
- Coach teams on engineering practices, delivery cadence, and operational readiness

### Goals
- Deliver predictable execution and technical quality
- Maintain team health, focus, and sustainable throughput
- Reduce delivery friction and unblock cross-functional dependencies

### Typical Communication
- Delivery planning and weekly operational reviews
- Technical design and architecture discussions
- Dependency and escalation conversations with PM and cross-functional leads
- Release coordination and deployment readiness check-ins

### Interaction with Existing Roles
- Works with Product Managers to sequence roadmap priorities and manage delivery constraints
- Partners with Project Managers to align milestones, dependencies, and status reporting
- Supports Developers by clarifying technical ownership and prioritization
- Coordinates with Security Engineers, QA Leads, and Support partners for release quality and readiness

---

## QA Leads / Test Managers

### Role Summary
QA Leads define quality strategy, validation approaches, and release readiness standards. They ensure the team ships features that meet acceptance criteria and are reliable for users.

### Responsibilities
- Define test strategy, quality gates, and validation plans
- Own acceptance testing, regression coverage, and release readiness criteria
- Identify test automation opportunities and quality risks early in the lifecycle
- Partner with engineering and product on acceptance criteria and defect triage
- Support release decisions based on risk and test evidence

### Goals
- Improve confidence in feature quality and user experience
- Minimize defect escape and release instability
- Align testing with delivery speed and business risk

### Typical Communication
- Sprint planning and backlog refinement with acceptance criteria validation
- QA review and defect triage discussions
- Release readiness reviews and go/no-go recommendations
- Post-release quality assessment with product and support teams

### Interaction with Existing Roles
- Works with Developers to define testability and acceptance checks
- Collaborates with Product Managers on feature quality expectations and user-facing outcomes
- Partners with Project Managers on milestone risk, release planning, and issue prioritization
- Coordinates with Support and Customer Success on recurring issues and known quality gaps

---

## Customer Success / Support Partners

### Role Summary
Customer Success and Support partners connect delivery teams to real user feedback, service issues, and operational signals. They ensure customer impact informs planning, releases, and ongoing improvement.

### Responsibilities
- Capture user feedback, friction points, and recurring support trends
- Help categorize customer-impacting issues and prioritize resolution
- Provide context on service reliability, incident patterns, and user experience
- Share release and change impact information with support and customer-facing teams
- Contribute to post-incident and post-release learning

### Goals
- Improve customer satisfaction and product adoption
- Close feedback loops between users and delivery teams
- Reduce preventable support escalations and service disruption

### Typical Communication
- Weekly feedback and issue review
- Support triage and incident updates
- Stakeholder updates around release readiness and customer-impacting issues
- Retrospective and continuous improvement follow-ups

### Interaction with Existing Roles
- Shares customer insights with Product Managers to inform prioritization
- Supports Project Managers and Engineering Managers with escalation context and dependency awareness
- Works with Developers and QA Leads to validate issues and confirm fixes
- Helps Stakeholders understand customer impact and rollout implications

---

## Cross-functional Accountability Matrix

Use the following model to clarify ownership across the project lifecycle:

- Scope ownership: Product Manager and Engineering Manager / Tech Lead
- Delivery coordination: Project Manager
- Technical implementation: Developers and Engineering Manager / Tech Lead
- Quality and release readiness: QA Lead / Test Manager
- Security assurance: Security Engineer
- Customer and support insight: Customer Success / Support Partner
- Stakeholder communication: Project Manager and Product Manager
- Risk management: Project Manager, Security Engineer, and delivery leads

This matrix helps reduce ambiguity during planning, execution, and release by making ownership explicit and aligning decision-making across functions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles should be applied consistently alongside the core PM, Product, and Developer personas to improve cross-functional collaboration and accountability.

