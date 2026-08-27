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

### Interaction with Other Roles
- Work with QA/Testing Leads to understand acceptance criteria and test approaches
- Collaborate with Tech Leads on architecture and design decisions
- Receive prioritized work from Product Managers
- Report blockers and risks to Project Managers
- Follow security and compliance guidance from Security Leads

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
- Partner with Project Managers on delivery timelines
- Work with Stakeholders/Sponsors to align on business requirements and priorities
- Collaborate with Developers on feasibility and technical trade-offs
- Define quality standards with QA/Testing Leads
- Engage Tech Leads on architectural implications

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
- Partner with Product Managers on prioritization and scope
- Escalate risks and blockers involving Stakeholders/Sponsors
- Coordinate release schedules with Operations/Release Managers
- Track quality metrics with QA/Testing Leads
- Monitor technical risks flagged by Tech Leads

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and validation that software meets acceptance criteria and quality standards before release. They ensure that all deliverables meet quality thresholds and minimize defects reaching production.

### Responsibilities
- Collaborate with Product Managers and Developers to define acceptance criteria and quality standards
- Create and maintain test plans (unit, integration, end-to-end, performance)
- Coordinate manual and automated testing activities
- Validate that acceptance criteria are met before marking work as complete
- Identify quality gaps and work with Developers on root causes
- Prepare and execute smoke test scenarios for releases
- Track quality metrics and report findings to the team

### Goals
- Ensure all deliverables meet quality and acceptance standards
- Minimize defects reaching production
- Enable fast, confident releases
- Support rapid feedback cycles for developers and product teams

### Typical Communication
- Sprint planning and refinement (define test approach)
- Daily standups (quality blockers and test results)
- PR reviews (test coverage and acceptance validation)
- Release planning (smoke test preparation)
- Post-incident reviews (identify systemic quality issues)

### Interaction with Other Roles
- Work with Developers on test-driven development practices and test coverage
- Validate acceptance criteria defined by Product Managers
- Provide quality assurance sign-off for Project Managers
- Coordinate with Tech Leads on test infrastructure and automation strategy
- Partner with Operations/Release Managers on smoke tests and release validation
- Escalate critical quality issues to Project Managers

---

## Tech Lead / Engineering Manager

### Role Summary
Tech Leads own technical architecture decisions, mentor team members, and manage technical risks. They enable the team to maintain code quality, reduce technical debt, and support professional growth.

### Responsibilities
- Conduct technical design reviews and architecture decisions
- Mentor developers on best practices, design patterns, and technical standards
- Manage and prioritize technical debt
- Develop team capabilities and support career growth
- Identify and mitigate technical risks
- Collaborate on technology selections and framework decisions
- Lead code quality and testing standards discussions

### Goals
- Maintain code quality and architectural consistency
- Reduce technical risk and technical debt
- Enable team growth and professional development
- Support scalable, maintainable system design

### Typical Communication
- Design reviews (technical architecture and decisions)
- Technical escalations (complex problems and trade-offs)
- Sprint refinement (sizing and technical estimates)
- One-on-ones with team members (mentoring and growth)
- Architecture documentation and decision records

### Interaction with Other Roles
- Guide Developers on technical decisions and best practices
- Collaborate with QA/Testing Leads on test architecture and automation strategy
- Work with Project Managers on technical risk escalation
- Partner with Product Managers on technical feasibility and architectural implications
- Coordinate with Security Leads on secure coding practices
- Support Operations/Release Managers on deployment and monitoring concerns

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors are executives or business owners who fund and prioritize initiatives. They define business requirements, approve scope and budget, and ensure projects deliver business value.

### Responsibilities
- Define business requirements and success criteria
- Approve project scope, budget, and resource allocation
- Attend milestone reviews and provide feedback
- Escalate business risks and resolve priority conflicts
- Communicate business context and rationale to the team
- Make key trade-off decisions on scope, schedule, and quality

### Goals
- Ensure project delivers expected business value
- Manage resource allocation and budget efficiently
- Maintain stakeholder alignment and satisfaction
- Enable fast decision-making and risk resolution

### Typical Communication
- Milestone reviews and demo attendance
- Escalation paths for priority and scope decisions
- Budget and resource approval decisions
- Status updates on business impact and outcomes
- Ad-hoc decisions on trade-offs and changes

### Interaction with Other Roles
- Partner with Product Managers on business priorities and outcomes
- Work with Project Managers on escalations and decisions
- Approve resources and budget in collaboration with Project Managers
- Receive quality and delivery updates from Project Managers
- Engage Developers and Tech Leads during critical reviews

---

## Security Lead

### Role Summary
Security Leads ensure compliance, conduct security reviews, and coordinate incident response. They minimize security risks and ensure projects meet compliance requirements.

### Responsibilities
- Conduct security design reviews during project planning
- Perform vulnerability assessments and security testing
- Validate compliance with security standards and regulations
- Coordinate security incident response
- Define and enforce secure coding practices
- Maintain security runbooks and incident procedures
- Track security metrics and audit findings

### Goals
- Minimize security risk and vulnerabilities
- Ensure compliance with security standards and regulations
- Enable rapid, effective incident response
- Build security awareness across the organization

### Typical Communication
- Security reviews in planning and design phases
- Risk escalation for security-related concerns
- Incident communication and coordination
- Security training and awareness sessions
- Post-incident reviews (blameless retrospectives)

### Interaction with Other Roles
- Conduct design reviews with Tech Leads and Developers
- Define secure coding standards and practices
- Work with Project Managers on security risk escalation
- Coordinate with Operations/Release Managers on security deployment and monitoring
- Partner with QA/Testing Leads on security testing approach
- Collaborate with Product Managers on security requirements

---

## Operations / Release Manager

### Role Summary
Operations and Release Managers coordinate deployments, monitor production health, and manage operational runbooks. They enable reliable releases and rapid incident response.

### Responsibilities
- Coordinate deployment activities and release windows
- Monitor production systems and health metrics
- Triage and coordinate response to production incidents
- Maintain and update operational runbooks and playbooks
- Ensure deployment procedures and infrastructure are ready
- Verify post-deployment health and stability
- Track deployment metrics and reliability indicators

### Goals
- Enable reliable, confident releases
- Minimize deployment risk and downtime
- Enable rapid incident response and recovery
- Maintain high system availability and performance

### Typical Communication
- Release planning and coordination
- Deployment windows and go/no-go decisions
- Production monitoring and alerting
- Incident triage and coordination
- Post-incident reviews and action items

### Interaction with Other Roles
- Coordinate with Project Managers on release schedules and timelines
- Work with QA/Testing Leads to prepare and execute smoke tests
- Partner with Tech Leads on deployment procedures and monitoring
- Collaborate with Developers on troubleshooting and incident response
- Engage Security Leads on security deployment procedures
- Report production metrics and availability to Project Managers and Stakeholders

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interaction with Other Roles" sections to understand cross-functional collaboration and communication patterns.
