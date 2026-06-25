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

## QA/Testing Lead

### Role Summary
QA/Testing Leads oversee quality assurance strategy, test planning, and validation activities. They ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define and maintain test plans aligned with feature acceptance criteria
- Execute or coordinate manual and automated testing activities
- Report quality metrics and identify defects before release
- Advise on testability during design and backlog refinement
- Participate in pre-release smoke testing and post-deployment verification

### Goals
- Prevent defects from reaching production
- Validate that features meet user expectations and acceptance criteria
- Provide early feedback on testability and risk

### Typical Communication
- QA status updates in daily standups
- Test plan reviews during sprint planning
- Defect reports and quality metrics in weekly syncs
- Collaboration with developers on test automation strategies

### Interaction with Other Roles
- Works with **Developers** to clarify testability and acceptance criteria
- Partners with **Project Managers** to report quality metrics and blockers
- Coordinates with **Product Managers** on feature acceptance validation
- Advises **Technical Architects** on testing infrastructure needs

---

## Technical Architect / Tech Lead

### Role Summary
Technical Architects provide technical direction, design guidance, and oversight of complex architectural decisions. They ensure solutions are scalable, maintainable, and aligned with technical strategy.

### Responsibilities
- Review and provide input on technical design and architecture decisions
- Identify technical risks and propose mitigation strategies
- Mentor developers on best practices and code quality standards
- Coordinate cross-team technical dependencies and integrations
- Advise on technology choices and debt management

### Goals
- Maintain technical excellence and system health
- Reduce technical debt and future maintenance burden
- Ensure scalability and performance of solutions

### Typical Communication
- Design reviews before implementation
- Technical risk assessment in planning meetings
- Architecture decisions documented in ADRs (Architecture Decision Records)
- Code review guidance and mentoring sessions

### Interaction with Other Roles
- Guides **Developers** on architectural patterns and best practices
- Advises **Project Managers** on technical risks and timeline implications
- Collaborates with **QA/Testing Leads** on test infrastructure design
- Coordinates with **Security & Compliance Leads** on secure architecture patterns

---

## Security & Compliance Lead

### Role Summary
Security and Compliance Leads ensure that projects meet security, privacy, and regulatory requirements. They oversee security scanning, vulnerability management, and compliance documentation.

### Responsibilities
- Review features for security and privacy implications
- Oversee security scanning in CI/CD pipelines
- Manage vulnerability assessments and remediation
- Ensure compliance with relevant regulations and standards
- Coordinate incident response and post-incident reviews
- Review and approve release notes and deployment procedures

### Goals
- Protect customer data and system integrity
- Maintain compliance with regulatory requirements
- Reduce security incidents and vulnerabilities

### Typical Communication
- Security review during design and PR stages
- Vulnerability reports and remediation status in weekly syncs
- Escalation of security incidents to on-call responder
- Compliance checklists and audit documentation

### Interaction with Other Roles
- Reviews code and designs with **Developers** for security implications
- Advises **Project Managers** on compliance and security timelines
- Partners with **Technical Architects** on secure architecture patterns
- Coordinates with **QA/Testing Leads** on security testing requirements
- Reports to **Stakeholders/Sponsors** on compliance status

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and help teams improve their delivery processes. They act as servant leaders supporting the team's success.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Track sprint metrics and team velocity
- Identify and help resolve impediments and blockers
- Coach the team on agile practices and continuous improvement
- Support process optimization and process adherence

### Goals
- Enable consistent, predictable delivery
- Improve team collaboration and communication
- Foster a culture of continuous improvement and psychological safety

### Typical Communication
- Facilitation of all agile ceremonies
- Sprint metrics and health reports
- Action item tracking and follow-up
- Process improvement recommendations

### Interaction with Other Roles
- Facilitates collaboration between all team members
- Removes blockers escalated by **Developers**, **QA/Testing Leads**, and other roles
- Supports **Project Managers** in meeting delivery commitments
- Coaches the team on working agreements and continuous improvement

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, prioritization guidance, and approval for project decisions. They represent business needs and resource constraints.

### Responsibilities
- Define business requirements and success metrics
- Provide prioritization guidance and trade-off decisions
- Approve project charters and major changes in scope
- Communicate project status to broader organization
- Provide funding and resource support

### Goals
- Ensure project delivers business value
- Align project priorities with organizational strategy
- Enable clear governance and decision-making

### Typical Communication
- Monthly stakeholder updates and status briefings
- Approval gates during project initiation and major milestones
- Ad-hoc escalations for business-critical decisions
- Executive-level reporting and risk communication

### Interaction with Other Roles
- Provides business context and success metrics to **Product Managers**
- Receives project status and risk updates from **Project Managers**
- Approves major decisions and resource allocations
- Escalates business-critical issues to leadership

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When running projects, assign team members to roles and reference these definitions for accountability and communication expectations.
