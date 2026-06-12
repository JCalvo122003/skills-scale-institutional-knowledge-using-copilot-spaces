# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## Personas Quick Index
- [Developers](#developers)
- [Product Managers](#product-managers)
- [Project Managers](#project-managers)
- [Delivery Lead](#delivery-lead-or-team-lead)
- [Technical Program Manager (TPM)](#technical-program-manager-tpm)
- [UX Researcher](#ux-researcher)
- [Security Liaison / Security Engineer](#security-liaison--security-engineer)
- [SRE / Platform Engineer](#sre--platform-engineer)
- [Release Manager](#release-manager)
- [Data Analyst / Analytics Owner](#data-analyst--analytics-owner)

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

## Delivery Lead (or Team Lead)

### Role Summary
Coordinates day-to-day delivery across multiple squads or a large feature area. Removes blockers and ensures smooth workflow through the development pipeline.

### Responsibilities
- Drive sprint/iteration commitments and remove cross-team blockers
- Coordinate cross-team dependencies and integration points
- Maintain delivery-level schedule and ensure work flows through the pipeline
- Identify and escalate risks early

### Goals
- Maximize team velocity and flow
- Minimize context-switching and rework
- Ensure visibility into delivery status and bottlenecks

### Typical Communication
- Daily standup facilitation and blocker resolution
- Dependency coordination meetings with other teams
- Escalations to Project Manager when wider impact is detected
- Weekly alignment with PM and PdM

---

## Technical Program Manager (TPM)

### Role Summary
Manages technical dependencies, release schedules, and cross-functional engineering coordination. Ensures technical readiness and integration across teams.

### Responsibilities
- Own cross-team technical plans, integration testing, and rollout sequencing
- Facilitate design/architecture coordination and technical risk mitigation
- Manage release gates and deployment coordination for complex features
- Track technical blockers and coordinate resolution

### Goals
- Ensure technical readiness for releases
- Reduce integration risk and rework
- Improve cross-team technical communication

### Typical Communication
- Architecture and design coordination meetings
- Release readiness reviews
- Collaboration with Developers, SRE, and PM to sequence work
- Technical dependency tracking and escalation

---

## UX Researcher

### Role Summary
Leads user research and ensures design decisions are evidence-based. Translates user needs into actionable insights for product and engineering.

### Responsibilities
- Plan and run user interviews, usability tests, and synthesize findings
- Translate research into prioritized recommendations and acceptance criteria
- Share results with Product Manager and design/engineering to inform backlog
- Validate proposed solutions with users

### Goals
- Ensure product decisions are grounded in user needs
- Reduce rework due to usability issues
- Accelerate product-market fit

### Typical Communication
- Research plans and findings shared with PdM
- Acceptance criteria and usability expectations communicated to Developers and QA
- Monthly research sharing sessions with the team

---

## Security Liaison / Security Engineer

### Role Summary
Ensures security requirements are integrated into planning and delivery. Serves as the primary contact for security review and compliance.

### Responsibilities
- Conduct security reviews and threat modeling for new features
- Define security-related acceptance criteria and coordinate remediation
- Serve as contact for security incidents and compliance checks
- Review architecture and design for security implications

### Goals
- Prevent security vulnerabilities in production
- Ensure compliance with regulatory and organizational standards
- Build security awareness across teams

### Typical Communication
- Security review gates in release process
- Design and code review comments on security topics
- Escalation to Product Lead for critical findings
- Quarterly security training and updates

---

## SRE / Platform Engineer

### Role Summary
Owns reliability, observability, and production operations. Ensures systems are built for safe, scalable deployment.

### Responsibilities
- Define SLOs, monitor key metrics, and run incident response playbooks
- Collaborate on deployment strategies and rollback procedures
- Support CI/CD and automation to reduce manual release risk
- Provide runbooks and operational guidance

### Goals
- Maintain high system reliability and uptime
- Enable rapid, safe deployments
- Minimize mean time to recovery (MTTR) for incidents

### Typical Communication
- Close collaboration with Developers during feature planning (for observability, scalability)
- Deployment coordination with Release Manager
- Operational risk communication to PM
- Incident post-mortems and action items

---

## Release Manager

### Role Summary
Coordinates release activities, notes, and stakeholder communication. Ensures releases are well-planned, tested, and communicated.

### Responsibilities
- Prepare release notes, schedule deployment windows, and confirm rollback plans
- Validate that pre-release checklists and smoke tests are complete
- Coordinate post-release verifications and stakeholder announcements
- Maintain release documentation and runbooks

### Goals
- Execute on-time, incident-free releases
- Maintain stakeholder confidence in release quality
- Reduce release-day surprises and manual work

### Typical Communication
- Weekly release planning meetings with PM, TPM, SRE, and QA
- Pre-release readiness checklist reviews
- Release notes and stakeholder communication
- Post-release verification and sign-off

---

## Data Analyst / Analytics Owner

### Role Summary
Defines metrics and ensures instrumentation supports success measurement. Analyzes feature impact and informs future planning.

### Responsibilities
- Define and validate success metrics and dashboards
- Ensure telemetry is in place for experiments and features
- Analyze release impact and report outcomes to Product Manager and PM
- Support A/B testing and feature rollout analysis

### Goals
- Enable data-driven decision making
- Measure product impact and iterate based on results
- Reduce guesswork in roadmap prioritization

### Typical Communication
- Metric definition sessions with Product Manager
- Instrumentation requirements with Developers
- Weekly analytics dashboards and reports
- Post-release impact analysis and recommendations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas in your project charters and process docs to clarify ownership and accountability.
