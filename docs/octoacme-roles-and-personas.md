# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Note on team size:** On smaller teams, one person may cover multiple roles. These personas describe responsibilities, not headcount. Use them to ensure every responsibility has a clear owner, even when the same individual wears several hats.

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

### Interaction with Other Roles
- **Product Managers:** receive acceptance criteria and clarify requirements
- **Project Managers:** report progress, surface blockers, and participate in planning ceremonies
- **QA / Test Engineers:** collaborate on testability, share test results, and address defects
- **Technical Leads / Architects:** follow architectural guidance and raise design questions
- **DevOps / Platform Engineers:** coordinate on environment needs and deployment readiness

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

### Interaction with Other Roles
- **Project Managers:** align on timelines, scope changes, and resourcing trade-offs
- **Developers:** provide acceptance criteria, answer questions, and validate outcomes
- **Designers / UX Researchers:** co-define user needs and review design proposals
- **Stakeholders / Executive Sponsors:** gather business requirements and present roadmap updates
- **Support / Customer Success:** incorporate customer feedback and prioritize pain-point fixes

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

### Interaction with Other Roles
- **Product Managers:** align on scope, priorities, and change decisions
- **Developers:** facilitate planning and track delivery progress
- **Engineering Managers:** coordinate capacity, staffing, and escalations
- **Delivery Leads / Scrum Masters:** share delivery cadence ownership and ceremony facilitation
- **Stakeholders / Executive Sponsors:** provide status updates and surface decisions that need escalation
- **DevOps / Platform Engineers:** coordinate deployment windows and release readiness

---

## QA / Test Engineers

### Role Summary
QA / Test Engineers own test strategy, quality validation, and feature acceptance support. They ensure that software meets defined acceptance criteria and that quality is built in throughout delivery—not just checked at the end.

### Responsibilities
- Define and maintain the test strategy and test plans
- Implement and run automated and manual tests (unit, integration, end-to-end, regression)
- Validate feature acceptance criteria with Product Managers
- Track defects and work with Developers to resolve them
- Support release readiness reviews with sign-off on quality gates
- Promote testability and quality practices across the team

### Goals
- Ship high-quality features with minimal production defects
- Build confidence in releases through repeatable test coverage
- Reduce the cost of defect detection by catching issues early

### Typical Communication
- Bug reports and defect triage sessions
- Test result summaries during release readiness reviews
- Participation in sprint planning and demos to confirm acceptance criteria are testable

### Interaction with Other Roles
- **Developers:** collaborate on testability, share test results, and triage defects together
- **Product Managers:** clarify acceptance criteria and validate feature behavior against user needs
- **Project Managers:** provide release readiness status and flag quality-related risks
- **DevOps / Platform Engineers:** coordinate on test environment availability and CI pipeline coverage

---

## Engineering Managers

### Role Summary
Engineering Managers support team health, staffing, capacity planning, and professional development. They enable delivery by removing organizational blockers and ensuring their teams are set up for success.

### Responsibilities
- Manage team staffing, capacity, and allocation across projects
- Support career development and performance for direct reports
- Resolve escalations and organizational blockers
- Partner with Project Managers and Product Managers on feasibility and sequencing
- Champion engineering best practices and team culture

### Goals
- Maintain a healthy, motivated, and productive engineering team
- Ensure delivery commitments are realistic and achievable
- Enable long-term technical quality alongside short-term delivery

### Typical Communication
- 1:1s and team health check-ins
- Capacity and resourcing discussions with Project Managers
- Escalation handling for organizational or cross-team blockers

### Interaction with Other Roles
- **Project Managers:** align on realistic timelines, resource availability, and escalation paths
- **Product Managers:** discuss feasibility, prioritization trade-offs, and team capacity
- **Technical Leads / Architects:** align on technical direction and support engineering decisions
- **Developers:** provide coaching, remove obstacles, and manage career growth

---

## Designers / UX Researchers

### Role Summary
Designers and UX Researchers define user experience flows, interaction design, and usability validation. They ensure that what is built is useful, usable, and aligned with user mental models.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity design assets
- Define interaction patterns and accessibility requirements
- Validate design solutions with real users before and after release
- Maintain a consistent design system and visual language

### Goals
- Ensure product features are usable and meet real user needs
- Reduce rework by validating designs before implementation begins
- Improve customer satisfaction and adoption through quality UX

### Typical Communication
- Design reviews and feedback sessions with Product Managers and Developers
- Usability test reports and research findings shared during planning
- Design assets and prototypes in shared design tools (e.g., Figma)

### Interaction with Other Roles
- **Product Managers:** co-define user problems, validate design direction, and inform backlog priorities
- **Developers:** ensure implementation fidelity to approved designs and clarify interaction details
- **QA / Test Engineers:** provide design acceptance criteria including visual and accessibility expectations

---

## Delivery Leads / Scrum Masters

### Role Summary
Delivery Leads and Scrum Masters facilitate team ceremonies, remove process impediments, and continuously improve the team's execution flow. They focus on how the team works together, not on what is being built.

### Responsibilities
- Facilitate sprint planning, standups, retrospectives, and demos
- Identify and resolve delivery impediments
- Coach the team on agile or lean delivery practices
- Track iteration health, velocity, and improvement actions
- Partner with Project Managers on delivery coordination and reporting

### Goals
- Maintain a predictable and sustainable delivery cadence
- Increase team throughput and reduce waste in the delivery process
- Foster continuous improvement culture within the team

### Typical Communication
- Daily standup facilitation
- Sprint review and retrospective summaries
- Impediment logs and team health dashboards

### Interaction with Other Roles
- **Project Managers:** share delivery cadence ownership; align on milestone tracking and escalation
- **Developers:** coach on process, remove blockers, and support planning and estimation
- **Engineering Managers:** surface team health issues and process improvement opportunities
- **Product Managers:** ensure backlog readiness and that planning inputs are available ahead of sprints

---

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects provide technical direction, system design guidance, and trade-off decisions. They ensure the team builds solutions that are scalable, maintainable, and aligned with technical strategy.

### Responsibilities
- Define and communicate architectural patterns and technical standards
- Lead technical design reviews and major trade-off decisions
- Identify and mitigate technical risks during planning and execution
- Support Developers with implementation guidance and code review feedback
- Translate technical constraints into language that informs planning

### Goals
- Ensure the system is reliable, scalable, and maintainable long-term
- Reduce technical debt accumulation while enabling delivery speed
- Create shared technical understanding across the team

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Code review participation and design review sessions
- Technical risk inputs into the project risk register

### Interaction with Other Roles
- **Developers:** provide design guidance, review code, and unblock technical decisions
- **Product Managers:** communicate technical constraints that affect scope or timeline
- **Project Managers:** surface technical risks and dependencies that affect delivery plans
- **Engineering Managers:** align on technical direction and team capability needs
- **Security / Compliance:** coordinate on secure-by-design patterns and compliance constraints
- **DevOps / Platform Engineers:** define infrastructure and operational requirements

---

## Stakeholders / Executive Sponsors

### Role Summary
Stakeholders and Executive Sponsors provide strategic alignment, business context, funding authority, and escalation support. They are accountable for business outcomes and serve as champions for the project within the broader organization.

### Responsibilities
- Provide business goals, constraints, and strategic context
- Approve project initiation, scope changes, and significant resource decisions
- Participate in milestone reviews and staged go/no-go decisions
- Escalate or resolve cross-organizational blockers
- Communicate project outcomes to executive and business audiences

### Goals
- Ensure projects deliver measurable business value
- Maintain organizational confidence in delivery
- Enable timely decisions to unblock progress

### Typical Communication
- Monthly or milestone-based stakeholder updates
- Participation in kickoffs, go/no-go reviews, and release sign-offs
- Executive briefings and business outcome reviews

### Interaction with Other Roles
- **Product Managers:** provide business priorities, approve roadmaps, and receive progress updates
- **Project Managers:** receive status updates, escalation summaries, and decision requests
- **Engineering Managers:** collaborate on resourcing and organizational-level escalations

---

## Support / Customer Success

### Role Summary
Support and Customer Success represent the voice of the customer inside the delivery process. They surface operational readiness gaps, post-release feedback, and customer pain points that should influence prioritization and launch planning.

### Responsibilities
- Communicate customer issues, frequently asked questions, and feedback patterns to the product team
- Assess rollout readiness from a support and customer experience perspective
- Contribute to release communication plans and customer-facing announcements
- Identify training, documentation, and enablement needs for new features
- Participate in incident triage for customer-impacting issues

### Goals
- Ensure new features are supportable and customers are set up for success
- Reduce support volume by advocating for usability and documentation quality
- Maintain customer trust and satisfaction through responsive support processes

### Typical Communication
- Pre-release readiness reviews with Project Managers and Product Managers
- Feedback summaries and support ticket trend reports
- Contribution to release notes and help documentation

### Interaction with Other Roles
- **Product Managers:** provide customer feedback and help prioritize pain-point fixes
- **Project Managers:** flag operational readiness risks and contribute to rollout communication plans
- **Developers:** report reproducible bugs and validate fixes from a customer perspective
- **DevOps / Platform Engineers:** escalate operational incidents with customer impact

---

## Security / Compliance

### Role Summary
Security and Compliance roles review security-sensitive changes, define compliance controls, and ensure that projects meet regulatory and organizational security requirements throughout delivery—not just at release.

### Responsibilities
- Define security requirements and review high-risk changes during design and implementation
- Perform or coordinate security reviews and vulnerability assessments
- Maintain compliance checklists and support audit activities
- Participate in incident response and security escalations
- Partner with Technical Leads to promote secure-by-design practices

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure ongoing compliance with relevant regulations and standards
- Reduce organizational risk through proactive security engagement

### Typical Communication
- Security review sign-offs as part of release readiness
- Threat modeling sessions during planning for high-risk work
- Security findings and remediation tracking via the risk register

### Interaction with Other Roles
- **Developers:** review security-sensitive code and provide secure coding guidance
- **Technical Leads / Architects:** align on secure-by-design patterns and architecture decisions
- **Project Managers:** surface security risks and flag compliance requirements that affect timelines
- **DevOps / Platform Engineers:** define security controls for infrastructure and CI/CD pipelines

---

## DevOps / Platform Engineers

### Role Summary
DevOps and Platform Engineers own the CI/CD pipelines, deployment environments, observability infrastructure, and operational reliability of the platform. They enable fast, safe, and repeatable deployments.

### Responsibilities
- Build and maintain CI/CD pipelines and automation tooling
- Manage environments (staging, production) and deployment processes
- Implement observability: logging, metrics, alerting, and dashboards
- Support release readiness, rollback planning, and incident response
- Define and enforce infrastructure security controls
- Partner with Developers on environment needs and release automation

### Goals
- Enable fast, reliable, and safe deployments to production
- Maximize system availability and operational visibility
- Reduce manual toil through automation

### Typical Communication
- Deployment readiness checklists and release coordination
- Incident alerts, postmortems, and on-call handoffs
- Infrastructure change documentation and runbooks

### Interaction with Other Roles
- **Developers:** support environment setup, deployment debugging, and CI troubleshooting
- **Project Managers:** coordinate deployment windows, release timing, and rollback plans
- **Security / Compliance:** implement infrastructure security controls and pipeline guardrails
- **Technical Leads / Architects:** align on infrastructure and operational architecture decisions
- **Support / Customer Success:** respond to operational incidents with customer impact

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-roles-raci-matrix.md`](./octoacme-roles-raci-matrix.md) for a lightweight RACI-style accountability matrix showing how these roles map to key project activities.

