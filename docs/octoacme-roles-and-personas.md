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

## Delivery Manager

### Role Summary
Delivery Managers coordinate delivery across projects and teams. They support Project Managers with portfolio-level dependencies and escalations without replacing ownership of individual project plans.

### Responsibilities
- Identify cross-project dependencies and capacity constraints during planning
- Monitor portfolio delivery health and coordinate resolution of cross-team blockers
- Support release coordination and escalate delivery risks to stakeholders
- Use retrospective findings to improve cross-team delivery practices

### Goals
- Reduce dependency bottlenecks and improve delivery predictability
- Keep portfolio commitments and delivery risks visible

### Typical Communication
- Cross-team delivery syncs and dependency reviews
- Portfolio health reports and stakeholder escalations
- Release coordination updates and retrospective action reviews

### Interactions with Existing Roles
- Developers: Gather technical dependency and blocker information and help secure cross-team support
- Product Managers: Align roadmap dependencies and surface delivery constraints to inform prioritization
- Project Managers: Coordinate dependencies and escalations across projects while Project Managers maintain project schedules, risks, and execution cadence

---

## Engineering Manager / Tech Lead

### Role Summary
Engineering Managers / Tech Leads guide technical delivery and engineering quality. Engineering Managers focus on team capacity and development; Tech Leads focus on technical direction and implementation decisions.

### Responsibilities
- Define architecture guardrails and engineering quality standards
- Provide capacity, estimation, and technical sequencing inputs during planning
- Guide design reviews and help resolve technical risks during execution
- Assess technical release readiness and carry engineering improvements into retrospectives

### Goals
- Deliver sustainable, maintainable solutions within realistic engineering capacity
- Identify technical trade-offs early and maintain quality through release

### Typical Communication
- Technical design reviews and architecture decision records
- Capacity planning discussions and technical risk updates
- Engineering readiness reviews and retrospective improvement discussions

### Interactions with Existing Roles
- Developers: Provide technical guidance, review designs, and support implementation quality and growth
- Product Managers: Explain feasibility and technical trade-offs while Product Managers retain scope and backlog prioritization
- Project Managers: Supply estimates, sequencing, and capacity constraints to support realistic plans and risk tracking

---

## UX Designer / Researcher

### Role Summary
UX Designers / Researchers clarify user needs and shape accessible, usable experiences from discovery through post-release learning.

### Responsibilities
- Conduct user research and synthesize findings to inform problem framing
- Create interaction designs and prototypes for prioritized user journeys
- Validate usability and accessibility considerations before and during implementation
- Review implemented experiences and share research insights for future iterations

### Goals
- Ensure solutions address validated user needs
- Reduce usability barriers and design rework

### Typical Communication
- Research readouts and discovery workshops
- Design critiques, annotated prototypes, and developer handoffs
- Usability findings and accessibility review feedback

### Interactions with Existing Roles
- Developers: Clarify design intent, discuss implementation constraints, and review the delivered user experience
- Product Managers: Collaborate on problem framing, research priorities, and user-centered success criteria
- Project Managers: Plan research and design milestones, flag dependencies, and communicate validation risks to delivery timelines

---

## Customer Success Manager (CSM)

### Role Summary
Customer Success Managers connect customer needs with delivery teams and help customers prepare for releases and achieve value after rollout.

### Responsibilities
- Gather customer priorities and real-world usage pain points during discovery
- Provide customer impact and enablement inputs for planning
- Coordinate customer rollout readiness and support release communications
- Track post-release adoption feedback and share lessons for future improvements

### Goals
- Improve customer adoption and realized value
- Reduce rollout surprises and keep customer feedback actionable

### Typical Communication
- Customer feedback summaries and impact briefings
- Rollout readiness check-ins and enablement materials
- Post-release adoption reports and customer follow-ups

### Interactions with Existing Roles
- Developers: Share reproducible usage problems and clarify customer impact without directly committing engineering work
- Product Managers: Provide customer priorities and outcomes to inform backlog decisions
- Project Managers: Coordinate customer communication, enablement dependencies, and rollout timelines

---

## Security / Compliance Representative

### Role Summary
Security / Compliance Representatives guide teams on security risks and applicable compliance obligations throughout the project lifecycle, not only before release.

### Responsibilities
- Identify applicable security, compliance, and policy requirements during initiation and planning
- Review designs and planned changes for risks and required controls
- Track review evidence and validate remediation with the delivery team
- Assess policy alignment before release and escalate unresolved risks through the agreed approval process

### Goals
- Identify risks early and reduce late-stage compliance surprises
- Ensure release decisions are supported by documented controls and risk evidence

### Typical Communication
- Security design reviews and compliance requirement briefings
- Risk register updates and remediation tracking
- Release review findings and escalation records

### Interactions with Existing Roles
- Developers: Explain control requirements, review implementation evidence, and validate remediation actions
- Product Managers: Clarify mandatory requirements and risk trade-offs to inform compliance-aware scope decisions
- Project Managers: Schedule reviews, record risks and remediation owners, and coordinate required approvals before release

---

## Data Analyst / Analytics Owner

### Role Summary
Data Analysts / Analytics Owners help teams define trustworthy measures of success and evaluate project outcomes from initial baselines through post-release analysis.

### Responsibilities
- Define metric baselines and measurement plans during initiation and planning
- Guide event instrumentation and validate data and dashboard quality
- Analyze release impact against agreed success metrics
- Share findings and measurement limitations to inform retrospectives and future decisions

### Goals
- Make project outcomes measurable and reporting reliable
- Enable evidence-based prioritization and continuous improvement

### Typical Communication
- Metric definition workshops and instrumentation specifications
- Dashboard reviews and data quality updates
- Post-release impact reports and retrospective insights

### Interactions with Existing Roles
- Developers: Specify tracking needs and validate implemented events and data quality
- Product Managers: Agree on measurable outcomes and interpret results to inform product decisions
- Project Managers: Align analytics dependencies and reporting cadence with project milestones and retrospective reviews

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
