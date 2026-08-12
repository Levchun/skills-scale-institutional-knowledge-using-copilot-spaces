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

## Quality Assurance Lead

### Role Summary
The QA Lead owns the quality strategy, test planning, and acceptance criteria validation. They ensure all deliverables meet quality standards before release and work closely with Product Managers and Developers to define and validate acceptance criteria.

### Responsibilities
- Define and maintain the test strategy and test plan for each project
- Create and refine detailed acceptance criteria with the Product Manager and Developers
- Lead test execution, test automation, and manual testing efforts
- Identify quality risks early and escalate blockers that impact release readiness
- Validate that acceptance criteria are met before marking work as "Done"
- Collaborate with Developers on testability and design for quality
- Conduct pre-release smoke tests and post-deployment verification
- Maintain and improve test coverage and automation frameworks

### Goals
- Catch defects early to minimize production issues
- Ensure customer-facing features meet quality expectations and business requirements
- Reduce rework and accelerate release cycles through proactive testing
- Enable continuous delivery with confidence

### Interaction with Other Roles
- **Product Manager**: Aligns on acceptance criteria, success metrics, and quality standards
- **Developers**: Collaborates on test design, testability requirements, and code review from a quality perspective
- **Project Manager**: Updates on test status, quality risks, and release readiness
- **Stakeholders**: Provides quality assessments, release readiness reports, and UAT support
- **Technical Architect**: Advises on test infrastructure and performance criteria

### Typical Communication
- Quality gates and acceptance criteria review in sprint planning
- Test status reports and blocker escalations in daily standups
- Release readiness verification before deployment
- Post-incident analysis and quality improvement action items

---

## Technical Architect

### Role Summary
The Technical Architect designs the overall technical solution, evaluates architectural trade-offs, and ensures the system is scalable, maintainable, and aligned with organizational standards. They provide technical governance and mentor the team on best practices.

### Responsibilities
- Conduct architecture reviews and provide technical guidance on design decisions
- Evaluate technology choices and justify trade-offs based on project requirements
- Identify technical risks early and propose mitigation strategies
- Ensure adherence to coding standards, design patterns, and organizational best practices
- Review system design for scalability, security, performance, and maintainability
- Mentor Developers on architectural best practices and design patterns
- Collaborate on technical feasibility assessment during planning
- Define non-functional requirements (performance, security, reliability)

### Goals
- Deliver technically sound, maintainable solutions that scale with organizational growth
- Reduce technical debt and future rework through thoughtful architectural decisions
- Ensure system reliability, security, and performance
- Enable faster delivery cycles through good architectural foundations

### Interaction with Other Roles
- **Developers**: Provides architectural guidance, design reviews, and mentoring on technical decisions
- **Product Manager**: Advises on technical feasibility and constraints that impact product decisions
- **Project Manager**: Escalates architectural risks, dependencies, and timeline impacts
- **QA Lead**: Collaborates on performance criteria, security testing, and non-functional requirements
- **Release Manager**: Advises on deployment architecture and infrastructure considerations

### Typical Communication
- Architecture design reviews before implementation begins
- Technical risk assessment and mitigation planning in project planning
- Code review comments and design guidance during execution
- Post-incident technical analysis and architectural improvements

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business stakeholders and the delivery team, clarifying requirements, validating that solutions meet business needs, and ensuring alignment with organizational goals. They translate business problems into actionable requirements.

### Responsibilities
- Gather and document business requirements from stakeholders and customers
- Clarify ambiguous requirements and identify gaps in understanding
- Work with Product Manager to define clear, testable acceptance criteria
- Validate that delivered solutions meet business objectives and success metrics
- Support user acceptance testing (UAT) and sign-off from business stakeholders
- Document business processes, workflows, and rules
- Identify and communicate business constraints and dependencies
- Support change management and stakeholder communication for releases

### Goals
- Ensure delivered features deliver measurable business value
- Reduce scope creep through clear requirements and stakeholder alignment
- Improve stakeholder satisfaction and adoption through validation and communication
- Minimize rework due to misunderstood requirements

### Interaction with Other Roles
- **Product Manager**: Collaborates on requirements gathering, prioritization, and success metrics
- **Developers**: Clarifies business rules, edge cases, and validates technical implementation against business intent
- **QA Lead**: Supports UAT, acceptance criteria validation, and business scenario testing
- **Stakeholders**: Serves as primary liaison for requirements gathering, feedback, and sign-off
- **Project Manager**: Updates on requirements changes and business-side dependencies or risks

### Typical Communication
- Requirements workshops and stakeholder interviews during planning
- Acceptance criteria refinement and clarification during sprint execution
- UAT coordination and sign-off before release
- Stakeholder updates on progress and business impact

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master (or Agile Coach in non-Scrum frameworks) facilitates the team's agile ceremonies, removes blockers, coaches the team on process adherence, and fosters continuous improvement. They enable the team to self-organize and deliver effectively.

### Responsibilities
- Facilitate sprint ceremonies: planning, standups, reviews, and retrospectives
- Remove or escalate blockers that impede team progress
- Coach the team on agile principles, values, and practices
- Maintain and communicate project metrics (velocity, burndown, cycle time)
- Identify process improvements and work with the team to implement them
- Protect the team from scope changes and external interruptions
- Support collaboration and psychological safety within the team
- Escalate team risks and dependencies to Project Manager or Product Lead

### Goals
- Enable the team to self-organize and make fast decisions
- Improve team velocity and predictability over time
- Foster a culture of continuous improvement and learning
- Maintain team focus and reduce waste through effective process management

### Interaction with Other Roles
- **Project Manager**: Collaborates on timeline, dependencies, and risk escalation
- **Product Manager**: Facilitates backlog refinement and prioritization ceremonies
- **Developers**: Coaches on agile practices and removes team impediments
- **All team members**: Facilitates ceremonies and coaches on process adherence
- **Stakeholders**: Communicates team status and manages expectations on delivery cadence

### Typical Communication
- Daily standups and sprint ceremonies facilitation
- Retrospective action item tracking and follow-up
- Velocity and progress reports to Project Manager and Product Manager
- Process improvement proposals and coaching conversations

---

## Release Manager

### Role Summary
The Release Manager coordinates deployment activities, manages release calendars, ensures smooth rollouts to production, and owns the release readiness verification process. They minimize release risk through planning, coordination, and post-deployment validation.

### Responsibilities
- Create and maintain release calendars and deployment schedules
- Coordinate cross-team dependencies for releases (deployment, support, documentation)
- Prepare and maintain release notes with changes, migration steps, and known issues
- Conduct pre-deployment verification and readiness reviews
- Coordinate deployment activities and communicate status to stakeholders
- Run post-deployment smoke tests and production verification
- Coordinate rollback procedures if issues are discovered post-deployment
- Support incident response for release-related issues
- Maintain release documentation and deployment runbooks

### Goals
- Execute releases with minimal risk and zero unplanned downtime
- Communicate release status clearly to all stakeholders
- Enable rapid, confident deployments through preparation and coordination
- Minimize mean time to recovery (MTTR) if issues occur

### Interaction with Other Roles
- **Developers**: Coordinates code delivery and deployment readiness verification
- **QA Lead**: Ensures all quality gates are met before deployment; coordinates smoke testing
- **Product Manager**: Communicates release timeline, features, and business impact
- **Project Manager**: Updates on release schedule, dependencies, and risks
- **Operations / Infrastructure**: Coordinates deployment, infrastructure changes, and monitoring
- **Support / Customer Success**: Communicates release notes and manages customer impact

### Typical Communication
- Release schedule updates and deployment coordination meetings
- Release readiness verification checklist and sign-off
- Deployment day status updates and incident communication
- Post-deployment verification and release closure

---

## How These Personas Are Used in the Exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understanding these roles helps teams align on responsibilities, accountability, and communication patterns.
- Consider which personas are relevant to your specific project or organizational context.
