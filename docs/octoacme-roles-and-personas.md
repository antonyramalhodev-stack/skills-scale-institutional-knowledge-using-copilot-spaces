# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

This expanded edition adds seven supporting personas to clarify accountability and collaboration across the delivery lifecycle.

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

## QA/Testing Lead

### Role Summary
QA/Testing Leads shape the quality strategy and validate that work meets acceptance criteria and agreed standards. They work with the team to build quality into delivery from planning through release.

### Responsibilities
- Define test approaches and coverage for features and releases
- Collaborate on acceptance criteria and the Definition of Done
- Plan and coordinate functional, integration, regression, and exploratory testing
- Triage defects, clarify severity, and track fixes through verification
- Report quality risks and release readiness
- Promote effective test automation and quality practices

### Goals
- Find defects early and reduce production issues
- Ensure delivered work meets acceptance criteria and user expectations
- Enable confident releases with useful, timely quality evidence

### Typical Communication
- Backlog refinement and planning to clarify testability and acceptance criteria
- Team check-ins to share testing progress, defects, and blockers
- Defect reports and test results linked to the relevant work
- Release readiness reviews to summarize coverage and open quality risks

### Key Interactions
- **With Developers**: agree on test approaches, review coverage, and reproduce and verify defects
- **With Product Managers**: refine acceptance criteria and confirm behavior against user needs
- **With Project Managers**: report quality status, defect trends, and risks to delivery plans
- **With Technical Leads/Architects**: identify quality risks in designs and agree on testing strategy for complex changes
- **With DevOps/Infrastructure Engineers**: coordinate test environments, deployment checks, and release verification
- **With Design/UX Leads**: validate usability and accessibility against intended user experiences

---

## Technical Lead/Architect

### Role Summary
Technical Leads/Architects guide technical design and architectural decisions so solutions remain secure, scalable, maintainable, and aligned with product needs. They provide technical direction while enabling Developers to make informed implementation choices.

### Responsibilities
- Define and review system designs, technical standards, and technology choices
- Identify architectural risks, constraints, and dependencies
- Guide code quality, security, performance, and maintainability practices
- Mentor Developers and support resolution of complex technical problems
- Make technical trade-offs visible to product and delivery partners
- Coordinate architecture decisions that span teams or services

### Goals
- Deliver solutions that meet current needs without compromising long-term maintainability
- Reduce technical risk, avoid unnecessary rework, and manage technical debt
- Give the team clear technical direction while supporting effective collaboration

### Typical Communication
- Architecture and technical design reviews
- Code reviews and focused technical discussions with Developers
- Planning conversations to explain complexity, dependencies, and trade-offs
- Risk and decision updates with product and project leads

### Key Interactions
- **With Developers**: review designs and code, provide guidance, and unblock complex implementation work
- **With Product Managers**: explain technical options and constraints that affect customer value and priorities
- **With Project Managers**: communicate technical risks, dependencies, and schedule implications
- **With QA/Testing Leads**: align on testability, quality risks, and validation of architectural changes
- **With DevOps/Infrastructure Engineers**: agree on platform, reliability, security, and deployment needs
- **With Design/UX Leads**: assess feasibility and performance implications of experience designs
- **With Scrum Masters/Agile Coaches**: identify technical impediments and improvement work affecting flow

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches help teams use effective agile practices, collaborate well, and improve how work flows. They facilitate team-owned processes rather than directing product or technical decisions.

### Responsibilities
- Facilitate planning, standups, reviews, retrospectives, and refinement when useful
- Help the team surface and resolve impediments or escalate those outside its control
- Support transparent work tracking and healthy, sustainable delivery practices
- Coach the team on continuous improvement and effective collaboration
- Help keep ceremonies focused on outcomes and inclusive participation

### Goals
- Enable predictable, sustainable progress and continuous learning
- Reduce delays caused by unresolved impediments or unclear team practices
- Help the team make and meet commitments while adapting to new information

### Typical Communication
- Facilitation of team ceremonies and working agreements
- Regular check-ins on blockers, team health, and improvement actions
- Coordination with project and product leads on process-related dependencies
- Retrospective follow-ups to track agreed improvements

### Key Interactions
- **With Developers**: facilitate collaboration, surface blockers, and support team-owned improvements
- **With Product Managers**: improve backlog readiness and facilitate productive prioritization and refinement
- **With Project Managers**: coordinate delivery rhythms, dependencies, and escalations without duplicating project oversight
- **With QA/Testing Leads**: make quality work and testing constraints visible in planning and team workflows
- **With Technical Leads/Architects**: help address technical impediments and make cross-team dependencies visible
- **With Design/UX Leads**: include design discovery and validation in team planning and feedback loops
- **With DevOps/Infrastructure Engineers**: coordinate work to resolve deployment or environment blockers

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders/Sponsors provide business context, represent affected groups, and support governance and prioritization decisions. Sponsors help ensure the project has a clear purpose, appropriate support, and timely decisions.

### Responsibilities
- Explain business goals, constraints, user needs, and organizational context
- Confirm sponsorship, funding, and governance expectations as applicable
- Make or escalate priority and scope decisions within their authority
- Review progress and outcomes against agreed objectives
- Connect the team with relevant users, subject-matter experts, and decision makers

### Goals
- Achieve measurable business outcomes and deliver value to intended users
- Ensure project decisions remain aligned with organizational priorities
- Resolve governance or resource issues promptly and transparently

### Typical Communication
- Project kickoff and milestone reviews to align on purpose and outcomes
- Periodic status updates and decisions on escalated scope, priority, or resource questions
- Reviews of product evidence and outcomes with relevant business groups

### Key Interactions
- **With Product Managers**: align on business outcomes, roadmap priorities, and trade-offs
- **With Project Managers**: receive delivery updates and resolve escalated governance, resource, or scope decisions
- **With Developers**: provide business context through the Product Manager and participate in demos or technical discussions when useful
- **With Product Operations**: use product metrics and analysis to inform investment and prioritization decisions
- **With Design/UX Leads**: understand user research and experience findings relevant to business goals
- **With QA/Testing Leads**: review significant quality risks that may affect acceptance or release decisions

---

## Product Operations

### Role Summary
Product Operations enables consistent, evidence-informed product decisions through shared processes, product data, and operational support. The role helps Product Managers and stakeholders understand product performance and improve how product work is coordinated.

### Responsibilities
- Define and maintain reliable product metrics, dashboards, and reporting practices
- Support instrumentation, data quality, and interpretation of product analytics
- Coordinate product planning and feedback processes across teams
- Synthesize customer feedback, usage signals, and operational insights
- Help teams make decisions using consistent evidence and definitions

### Goals
- Make product outcomes visible and actionable
- Improve the consistency and reliability of product data and processes
- Help teams learn from usage and feedback and make timely product decisions

### Typical Communication
- Regular product metrics reviews and concise analysis for decision makers
- Coordination with teams on analytics needs and data quality
- Sharing customer feedback themes and operational learnings
- Briefings that connect product performance to roadmap questions

### Key Interactions
- **With Product Managers**: provide analytics and operational context for prioritization, experiments, and outcome reviews
- **With Project Managers**: align reporting and planning processes and make status and outcome data consistent
- **With Developers**: coordinate instrumentation requirements and investigate data quality or implementation questions
- **With Stakeholders/Sponsors**: present evidence and explain trends to inform governance and investment decisions
- **With Design/UX Leads**: combine user research and usability findings with product usage data
- **With QA/Testing Leads**: coordinate quality and release signals that contribute to product performance analysis

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers provide the automation and platform capabilities needed to build, deploy, and operate software reliably. They partner with delivery teams to make environments and releases repeatable, observable, and secure.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Provision and operate development, test, and production infrastructure
- Support monitoring, logging, reliability, backup, and recovery practices
- Define and communicate infrastructure and operational constraints
- Coordinate release readiness, deployment verification, and rollback planning
- Promote secure and repeatable infrastructure and delivery practices

### Goals
- Enable safe, reliable, and repeatable deployments
- Reduce operational toil and infrastructure-related delivery delays
- Provide systems that meet agreed reliability, security, and performance needs

### Typical Communication
- Pipeline and infrastructure updates in team planning and status discussions
- Release readiness and deployment coordination
- Incident, reliability, and capacity reviews with technical and project leads
- Documentation of environment requirements and operational procedures

### Key Interactions
- **With Developers**: provide build and deployment tooling, environments, and operational guidance
- **With Technical Leads/Architects**: align platform architecture, reliability, security, and scaling decisions
- **With QA/Testing Leads**: provision test environments and coordinate automated checks and release verification
- **With Product Managers**: explain operational constraints and support product decisions involving reliability or platform capabilities
- **With Project Managers**: communicate infrastructure dependencies, release plans, and operational risks to schedules and stakeholders
- **With Scrum Masters/Agile Coaches**: surface and resolve environment or pipeline blockers affecting team flow

---

## Design/UX Lead

### Role Summary
Design/UX Leads guide user-centered design and ensure experiences are usable, coherent, and accessible. They connect user research and design decisions to product goals and partner with engineering to deliver and validate those experiences.

### Responsibilities
- Lead user research, interaction design, and usability validation
- Define and maintain design patterns and design system contributions
- Translate user needs into flows, prototypes, and implementation-ready guidance
- Advocate for accessibility, consistency, and usability throughout delivery
- Gather feedback and iterate on designs with users and cross-functional partners

### Goals
- Deliver intuitive and accessible experiences that address real user needs
- Improve consistency across product surfaces and reduce design ambiguity
- Validate design assumptions before and after implementation

### Typical Communication
- Research readouts, design reviews, and prototype walkthroughs
- Collaboration during discovery, refinement, and implementation
- Usability findings and design system guidance shared with delivery teams
- Feedback loops with users, Product Managers, and Developers

### Key Interactions
- **With Product Managers**: connect user needs and research findings to product goals, scope, and prioritization
- **With Developers**: clarify design intent, review implementation, and resolve interaction or accessibility questions
- **With Project Managers**: identify design dependencies and validation activities for delivery plans
- **With QA/Testing Leads**: agree on usability and accessibility checks and validate experience quality
- **With Technical Leads/Architects**: assess design feasibility and align on technical implications
- **With Stakeholders/Sponsors**: share user insights and validate that proposed experiences support intended outcomes
- **With Product Operations**: combine research insights with product analytics to evaluate experience outcomes
- **With Scrum Masters/Agile Coaches**: coordinate discovery and design validation with team workflows

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
