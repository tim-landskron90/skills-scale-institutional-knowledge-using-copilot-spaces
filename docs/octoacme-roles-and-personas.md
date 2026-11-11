# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A role describes a set of responsibilities; one person may hold multiple roles when appropriate for the project, provided ownership and decision authority remain clear.

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

## Project Sponsor

### Role Summary
The Project Sponsor is accountable for the business case, organizational backing, and intended outcomes of a project. The sponsor makes or secures decisions that are outside the project manager's authority.

### Responsibilities
- Confirm the project's strategic purpose, desired outcomes, and success expectations
- Secure appropriate organizational support and help resolve resource or policy barriers
- Make or escalate significant scope, funding, and priority decisions
- Review progress against expected outcomes and address escalations

### Interactions and Decision Boundaries
- Sets direction and success expectations with the Product Manager or Product Owner and Project Manager
- Delegates day-to-day planning and coordination to the Project Manager, receiving escalations when authority or resources are insufficient
- Consults affected stakeholders and accountable business owners before major decisions
- Does not replace the Product Manager's ongoing product prioritization or the Project Manager's delivery coordination

---

## Product Owner / Business Owner

### Role Summary
The Product Owner or Business Owner represents the business needs the project is intended to meet. This role clarifies and prioritizes requirements and confirms that delivered outcomes are acceptable for the intended use.

### Responsibilities
- Clarify business needs, requirements, and acceptance expectations
- Prioritize business-facing scope and resolve requirement questions
- Review deliverables and confirm whether acceptance criteria and intended outcomes are met
- Identify business impacts and communicate decisions to relevant stakeholders

### Interactions and Decision Boundaries
- Aligns desired outcomes and material trade-offs with the Project Sponsor
- Works with the Product Manager to keep requirements, roadmap priorities, and customer value aligned; where both roles exist, the Product Manager owns product direction while the Product Owner focuses on project-specific needs and acceptance
- Coordinates with the Project Manager on scope, decisions, dependencies, and review timing
- Provides timely requirements and acceptance feedback to Developers and the Delivery Lead; acceptance does not replace independent quality checks

---

## Delivery Lead / Technical Lead

### Role Summary
The Delivery Lead or Technical Lead coordinates the technical approach and day-to-day engineering execution for the project. This role guides technical decisions and delivery dependencies without taking over overall project coordination.

### Responsibilities
- Coordinate technical work, sequencing, and engineering dependencies
- Guide technical design and document significant technical decisions
- Surface technical risks, estimates, and capacity constraints
- Help ensure implementation meets agreed technical and operational standards

### Interactions and Decision Boundaries
- Partners with the Project Manager on sequencing, milestones, dependencies, and risk escalation; the Project Manager remains responsible for the integrated project plan
- Works with Developers on implementation and technical reviews
- Consults Subject Matter Experts and the Quality Lead where domain requirements or verification affect the technical approach
- Makes technical decisions within delegated authority and escalates decisions that affect scope, business outcomes, or commitments to the appropriate sponsor, product, or project role

---

## Subject Matter Expert

### Role Summary
A Subject Matter Expert (SME) contributes specialist knowledge about a business domain, user group, regulation, or technology needed for sound project decisions.

### Responsibilities
- Explain relevant domain rules, constraints, terminology, and established practices
- Review plans, requirements, risks, and deliverables for domain accuracy
- Identify domain-specific impacts and recommend mitigations
- Provide timely advice and evidence to support decisions and acceptance

### Interactions and Decision Boundaries
- Advises the Project Manager, Product Manager or Product Owner, and Delivery Lead; the accountable decision-maker retains ownership of decisions
- Collaborates with Developers to clarify specialist requirements and with the Quality Lead to identify appropriate checks
- Raises material risks or conflicting guidance through the Project Manager to the relevant sponsor or business decision-maker

---

## Change and Communications Lead

### Role Summary
The Change and Communications Lead coordinates stakeholder readiness and adoption activities when project changes affect people, teams, or business operations.

### Responsibilities
- Identify affected stakeholder groups and assess readiness and adoption needs
- Plan communications, engagement, and training with clear audiences and timing
- Coordinate feedback channels and track adoption concerns or actions
- Surface change impacts and readiness risks before release or rollout

### Interactions and Decision Boundaries
- Aligns communication and change plans with the Project Manager's milestones and the Project Sponsor's direction
- Works with the Product Manager or Product Owner to explain intended user and business impacts
- Coordinates content and timing with affected teams, Developers, and relevant Subject Matter Experts
- Advises on readiness; release or scope decisions remain with the designated project, product, and sponsor decision-makers

---

## Quality Lead

### Role Summary
The Quality Lead coordinates how the project verifies that deliverables meet agreed quality standards and acceptance expectations. The role may be held by a dedicated quality specialist or assigned to a qualified team member.

### Responsibilities
- Help define quality criteria, verification activities, and required evidence
- Coordinate reviews, testing, defect visibility, and quality-related risks
- Confirm that verification results are documented and gaps are escalated
- Promote quality practices throughout delivery rather than only at final acceptance

### Interactions and Decision Boundaries
- Works with Developers and the Delivery Lead to plan and perform technical verification
- Aligns acceptance and evidence expectations with the Product Owner or Business Owner and relevant Product Manager
- Coordinates quality checkpoints and unresolved risks with the Project Manager
- Reports evidence and recommends readiness; formal business acceptance and release decisions remain with their designated owners

---

## Applying Roles and Accountability
- These roles are options to assign according to project size, complexity, and risk; not every project needs a separate person for each role.
- A person may hold multiple roles on a small project, but the project should still identify who owns each decision and avoid assigning incompatible review and approval duties to the same person where independence is needed.
- At kickoff, document role owners, decision authority, escalation paths, and key handoffs. When responsibilities overlap, the Project Manager coordinates the process and records the accountable decision-maker.
- The Project Sponsor owns organizational backing and escalated business decisions; Product Managers and Product Owners clarify product and business value; the Project Manager coordinates delivery; and technical, domain, change, and quality leads provide specialist ownership within their areas.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
