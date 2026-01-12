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

### Interactions with Core Roles
- **Project Managers**: Provide effort estimates, report blockers and risks, coordinate on timelines and dependencies
- **Product Managers**: Clarify requirements and acceptance criteria, propose technical alternatives, provide feasibility input
- **QA Lead**: Collaborate on test strategy and automation, review test coverage, coordinate bug fixes
- **UX Designer**: Review design feasibility, implement UI components, provide feedback on design technical constraints
- **DevOps Engineer**: Work on CI/CD configurations, troubleshoot build issues, coordinate deployments
- **Business Analyst**: Clarify business rules and edge cases, validate technical implementations meet business requirements

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

### Interactions with Core Roles
- **Project Managers**: Align on timelines and resource allocation, prioritize competing initiatives, review project health metrics
- **Developers**: Collaborate on technical feasibility and trade-offs, clarify feature requirements, validate delivered solutions
- **QA Lead**: Define quality standards and release criteria, review test plans, make quality trade-off decisions
- **UX Designer**: Partner on user research and design direction, validate designs meet product vision, prioritize UX improvements
- **DevOps Engineer**: Coordinate feature flags and rollout strategies, review production metrics, plan infrastructure for new features
- **Business Analyst**: Leverage data analysis for prioritization, refine requirements based on business impact, validate success metrics
- **Stakeholders**: Gather input on roadmap priorities, communicate product strategy, demonstrate features

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

### Interactions with Core Roles
- **Product Managers**: Coordinate on roadmap timing and scope, facilitate trade-off decisions, escalate project risks
- **Developers**: Track progress and blockers, facilitate planning sessions, coordinate cross-team dependencies
- **QA Lead**: Ensure testing is planned and tracked, coordinate release readiness, track quality metrics
- **UX Designer**: Track design milestone delivery, coordinate design reviews, ensure design handoffs are complete
- **DevOps Engineer**: Coordinate deployment schedules, track infrastructure dependencies, manage release planning
- **Business Analyst**: Ensure requirements are documented and clear, track business metrics, facilitate stakeholder alignment
- **Stakeholders**: Provide regular status updates, manage expectations, facilitate decision-making and approvals

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy and coordinates all testing efforts across the project. They ensure that acceptance criteria are testable, coordinate test automation, and represent quality concerns during planning and release decisions.

### Responsibilities
- Define and maintain the quality strategy and test plan
- Coordinate testing efforts across unit, integration, and end-to-end tests
- Collaborate with Developers on test automation and coverage
- Review acceptance criteria for testability during planning
- Provide quality signoff before releases
- Track and report on quality metrics (defect rates, test coverage, flakiness)
- Facilitate bug triage and prioritization

### Goals
- Ensure high-quality releases with minimal production defects
- Maintain comprehensive test coverage and reduce manual testing overhead
- Build quality practices into the development process (shift-left)
- Improve feedback loops and reduce time to detect issues

### Interactions with Core Roles
- **Project Managers**: Participate in planning sessions, provide testing estimates, report on quality risks and blockers, coordinate release readiness
- **Product Managers**: Review acceptance criteria for clarity and testability, validate that features meet quality standards, provide input on quality trade-offs
- **Developers**: Collaborate on test automation strategy, review PRs for testability, pair on complex test scenarios, assist with debugging production issues
- **DevOps Engineer**: Work together on CI/CD pipeline integration, test automation infrastructure, and test environment management
- **UX Designer**: Validate user flows work as designed, coordinate usability testing sessions
- **Stakeholders**: Provide quality reports and release confidence metrics

### Typical Communication
- Daily standups for sprint-level testing coordination
- Test plan reviews during sprint planning
- Bug triage meetings with Developers and PM
- Quality signoff reports before releases

---

## UX Designer

### Role Summary
The UX Designer guides the user experience and ensures solutions are intuitive, accessible, and delightful. They create prototypes, conduct usability research, and collaborate with Product and Engineering to balance user needs with technical constraints.

### Responsibilities
- Create wireframes, prototypes, and high-fidelity designs
- Conduct user research and usability testing
- Define interaction patterns and visual design standards
- Collaborate on feature specifications to ensure usability
- Review implementations for design consistency
- Maintain design systems and component libraries
- Advocate for accessibility and inclusive design practices

### Goals
- Deliver intuitive user experiences that meet user needs
- Reduce friction and improve user satisfaction metrics
- Ensure design consistency across the product
- Validate designs through research and testing

### Interactions with Core Roles
- **Product Managers**: Collaborate on feature definitions, participate in user research, validate designs align with business goals and user needs
- **Developers**: Share design specs and prototypes, review implementations, work together on technical feasibility and design trade-offs
- **Project Managers**: Provide design effort estimates, communicate design milestone status, flag design-related risks or dependencies
- **QA Lead**: Coordinate on usability testing, ensure UI acceptance criteria are clear, validate that implementations match design intent
- **Business Analyst**: Share user insights and pain points, collaborate on requirements that affect user experience
- **Stakeholders**: Present design concepts for feedback, demonstrate prototypes during reviews

### Typical Communication
- Design reviews and critique sessions
- Usability testing readouts and recommendations
- Prototype sharing via design tools (Figma, Sketch, etc.)
- Implementation review comments during development

---

## DevOps Engineer

### Role Summary
The DevOps Engineer owns the CI/CD pipeline, infrastructure, and deployment automation. They ensure reliable, repeatable releases and work with the team to improve developer productivity through automation and tooling.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment processes
- Manage infrastructure, environments, and configuration
- Implement monitoring, logging, and observability solutions
- Automate repetitive tasks and improve deployment reliability
- Support incident response and production troubleshooting
- Coordinate release deployments and rollback procedures
- Ensure security and compliance in build and deployment processes

### Goals
- Achieve fast, reliable, and safe deployments
- Minimize deployment-related incidents and downtime
- Improve developer productivity through automation
- Maintain infrastructure reliability and scalability

### Interactions with Core Roles
- **Developers**: Collaborate on build configurations, assist with local development environment setup, provide CI/CD troubleshooting support
- **QA Lead**: Integrate automated tests into CI/CD pipelines, manage test environments, coordinate deployment of test builds
- **Project Managers**: Report on deployment schedules and infrastructure risks, provide effort estimates for infrastructure work
- **Product Managers**: Coordinate feature flags and progressive rollout strategies, provide production metrics and observability data
- **Business Analyst**: Ensure monitoring captures business-relevant metrics and analytics
- **Stakeholders**: Communicate deployment windows and maintenance schedules

### Typical Communication
- Weekly infrastructure reviews and capacity planning
- Post-deployment reports and incident retrospectives
- CI/CD pipeline status and improvement proposals
- On-call escalations and production incident coordination

---

## Business Analyst

### Role Summary
The Business Analyst bridges business needs and technical solutions. They refine requirements, analyze data to inform decisions, track success metrics, and ensure projects deliver measurable business value.

### Responsibilities
- Gather and document business requirements
- Translate business needs into clear, actionable specifications
- Analyze data and metrics to support decision-making
- Define and track success metrics and KPIs
- Facilitate workshops and requirements gathering sessions
- Create process flows, data models, and documentation
- Validate solutions meet business needs and compliance requirements

### Goals
- Ensure projects solve the right business problems
- Provide clear, actionable requirements to the delivery team
- Track and communicate business value and ROI
- Identify opportunities for process improvement

### Interactions with Core Roles
- **Product Managers**: Support product decisions with data analysis, help prioritize features based on business impact, refine requirements for clarity
- **Project Managers**: Provide requirements documentation, assist with scope definition, track business metrics for project reporting
- **Developers**: Clarify business rules and edge cases, review implementations for business logic accuracy, answer requirements questions
- **UX Designer**: Share user research and business context, collaborate on user flows that meet business needs
- **QA Lead**: Define business acceptance criteria, validate test cases cover business requirements
- **Stakeholders**: Facilitate requirements workshops, present analysis and recommendations, gather feedback on proposed solutions

### Typical Communication
- Requirements specification documents and user stories
- Data analysis reports and business case presentations
- Weekly stakeholder check-ins for requirements clarification
- Sprint planning participation for acceptance criteria review

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

