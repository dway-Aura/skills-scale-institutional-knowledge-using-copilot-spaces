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

## UX / Design Lead

### Role Summary
The UX / Design Lead owns the user experience vision for projects. They ensure features are usable, accessible, and aligned with customer needs, bridging the gap between product intent and technical implementation.

### Responsibilities
- Define user flows, wireframes, and prototypes for new features
- Conduct or coordinate user research and usability testing
- Collaborate with Product Managers on acceptance criteria that include UX requirements
- Partner with Developers to review implementation against design specs
- Participate in sprint reviews and QA to validate UX acceptance criteria

### Goals
- Deliver consistent, high-quality user experiences
- Reduce design-development rework through early collaboration
- Ensure accessibility and usability standards are met

### Typical Communication
- Design reviews and handoff sessions with developers
- Usability findings shared with Product Manager
- Participation in sprint planning and retrospectives

---

## Engineering Lead / Tech Lead

### Role Summary
The Engineering Lead / Tech Lead provides technical direction and architectural oversight for the delivery team. They ensure technical decisions align with long-term maintainability and project goals.

### Responsibilities
- Define and communicate technical architecture and design standards
- Lead technical design discussions and review significant PRs
- Identify, document, and escalate technical risks
- Support developers with guidance on complex implementation challenges
- Assess feasibility and scope implications of product requirements

### Goals
- Maintain a healthy, scalable, and well-tested codebase
- Reduce technical debt and unplanned work
- Bridge communication between engineering and product/project management

### Typical Communication
- Architecture decision records (ADRs) and design docs
- Code review comments and PR approvals
- Technical risk items surfaced in weekly syncs

---

## Security / Compliance Reviewer

### Role Summary
The Security / Compliance Reviewer ensures that all features and infrastructure changes meet security requirements and comply with relevant standards before release.

### Responsibilities
- Review new features and infrastructure changes for security vulnerabilities
- Validate security scans in CI and escalate unresolved findings
- Maintain and update the security incident runbook
- Participate in pre-release checklists and sign off on security readiness
- Coordinate with the on-call team for security incident response

### Goals
- Minimize security risk across the project lifecycle
- Ensure compliance with internal and external requirements
- Build security practices into delivery workflows

### Typical Communication
- Security review findings shared with Engineering Lead and PM
- Participation in pre-release reviews
- Incident communication following the security incident runbook

---

## DevOps / Platform Engineer

### Role Summary
The DevOps / Platform Engineer owns the deployment infrastructure, CI/CD pipelines, and operational reliability of the project's systems.

### Responsibilities
- Build and maintain CI/CD pipelines for automated testing and deployment
- Manage environment configuration (staging, production)
- Support and execute release deployments and rollback procedures
- Monitor system health dashboards and respond to on-call alerts
- Collaborate with developers to improve deployment reliability and speed

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment risk and mean time to recovery (MTTR)
- Provide observability into system health and performance

### Typical Communication
- Deployment status updates during release windows
- Infrastructure change notifications to Engineering Lead and PM
- On-call incident response coordination

---

## Business Sponsor / Stakeholder

### Role Summary
The Business Sponsor / Stakeholder provides executive support, business context, and final decision authority for the project. They act as the escalation point for business-impacting issues.

### Responsibilities
- Define and communicate the business case and strategic priority of the project
- Approve key milestones, scope changes, and resource investments
- Act as the Level 3 escalation point for blockers that cannot be resolved at the team or PM level
- Review and accept major deliverables and release outcomes
- Communicate project progress and decisions to senior leadership

### Goals
- Ensure the project delivers measurable business value
- Maintain executive alignment and stakeholder confidence
- Resolve strategic blockers quickly to protect delivery timelines

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Executive briefings on project status and risks
- Escalation decisions communicated to PM and Product Lead

---

## Data / Analytics Engineer

### Role Summary
The Data / Analytics Engineer builds and maintains the data pipelines, dashboards, and analytics infrastructure that enable data-informed decision-making across the project.

### Responsibilities
- Design and maintain data models, ETL pipelines, and reporting dashboards
- Partner with Product Managers to instrument success metrics
- Ensure data quality and reliability across environments
- Collaborate with DevOps on pipeline deployment and monitoring
- Support incident investigations with data analysis

### Goals
- Provide timely, accurate data to support product and delivery decisions
- Minimize data downtime and pipeline failures
- Enable self-service analytics for stakeholders

### Typical Communication
- Dashboard updates and metric reviews with Product Manager
- Pipeline incident alerts to DevOps and Engineering Lead
- Sprint participation for instrumentation and reporting tasks

---

## Technical Writer

### Role Summary
The Technical Writer owns the creation, maintenance, and quality of all project documentation, including user guides, API references, onboarding materials, and release notes.

### Responsibilities
- Produce and maintain user-facing and internal documentation
- Collaborate with Developers and UX/Design Lead to ensure accuracy
- Review and publish release notes for each release
- Establish and enforce documentation standards across the project
- Participate in sprint reviews to capture documentation requirements

### Goals
- Ensure all features are well-documented before release
- Reduce support burden through clear, accessible documentation
- Maintain a single source of truth for product knowledge

### Typical Communication
- Documentation reviews with Developers and UX/Design Lead
- Release note handoff to PM and Business Sponsor
- Onboarding material updates during project ramp-up

---

## Customer Success / Support Representative

### Role Summary
The Customer Success / Support Representative acts as the voice of the customer within the delivery team, surfacing user feedback, bug reports, and usability issues to improve product quality.

### Responsibilities
- Collect and synthesize customer feedback and support tickets
- Communicate known issues and workarounds to customers
- Participate in sprint reviews and release sign-offs
- Partner with Product Manager to prioritize customer-impacting issues
- Validate that release communications meet customer needs

### Goals
- Reduce customer-reported defects through early feedback loops
- Ensure customers are informed of changes and issues proactively
- Improve customer satisfaction and retention

### Typical Communication
- Feedback summaries shared with Product Manager and PM
- Participation in release reviews and QA sign-off
- Customer-facing announcements coordinated with Technical Writer

---

## Legal / Privacy Reviewer

### Role Summary
The Legal / Privacy Reviewer ensures that features and data practices comply with applicable laws, privacy regulations, and contractual requirements.

### Responsibilities
- Review features with legal or privacy implications (e.g., data collection, user consent)
- Advise on compliance with GDPR, CCPA, and other relevant regulations
- Collaborate with Security / Compliance Reviewer on overlapping concerns
- Participate in pre-release checklists for legally sensitive features
- Escalate unresolved legal risks to the Business Sponsor

### Goals
- Prevent compliance violations before release
- Reduce legal risk across the project lifecycle
- Ensure privacy-by-design is embedded in delivery workflows

### Typical Communication
- Legal review findings shared with Product Manager and Engineering Lead
- Participation in pre-release reviews for regulated features
- Escalation to Business Sponsor for high-risk legal decisions

---

## Release Manager

### Role Summary
The Release Manager coordinates and owns the end-to-end release process, ensuring that deployments are well-planned, properly communicated, and successfully executed.

### Responsibilities
- Own the release schedule and coordinate go/no-go decisions
- Ensure all pre-release criteria are met before deployment
- Coordinate release activities across DevOps, Engineering Lead, QA, and PM
- Manage release communications to stakeholders
- Lead post-release verification and incident response coordination

### Goals
- Deliver releases on schedule with minimal disruption
- Maintain clear accountability and communication throughout the release process
- Reduce mean time to recovery (MTTR) for release-related incidents

### Typical Communication
- Release status updates to PM, Engineering Lead, and Stakeholders
- Go/no-go decisions coordinated with DevOps and QA
- Post-release retrospectives and incident reviews

---

## Scrum Master / Agile Coach *(optional overlay role)*

### Role Summary
The Scrum Master / Agile Coach facilitates agile ceremonies, removes team impediments, and coaches the delivery team on agile practices to improve flow and predictability.

### Responsibilities
- Facilitate standups, sprint planning, retrospectives, and reviews
- Identify and remove impediments blocking team progress
- Coach team members on agile values, principles, and practices
- Track team velocity and help improve sprint predictability
- Collaborate with PM to maintain healthy team dynamics

### Goals
- Improve team delivery flow and reduce waste
- Foster a culture of continuous improvement and psychological safety
- Ensure agile ceremonies deliver value rather than overhead

### Typical Communication
- Daily facilitation of standups and sprint ceremonies
- Retrospective action items shared with PM
- Coaching sessions with individual team members and leads

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
