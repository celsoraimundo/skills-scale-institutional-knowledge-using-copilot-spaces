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

## Release Manager

### Role Summary
Release Managers orchestrate the end-to-end release process, ensuring features move from staging to production safely and on schedule. They coordinate across teams, manage release timelines, and oversee deployment quality gates.

### Responsibilities
- Coordinate release schedules and deployment windows
- Ensure all pre-release requirements are met (tests, security scans, documentation)
- Manage release branches and version control
- Execute deployment checklists and monitor post-deployment health
- Coordinate rollback procedures when necessary
- Maintain release notes and communicate changes to stakeholders

### Goals
- Deliver reliable, predictable releases with minimal downtime
- Reduce deployment-related incidents and rollbacks
- Maintain clear visibility into release status and risks

### Typical Communication
- Release planning meetings with Product and Engineering
- Deployment status updates during release windows
- Release notes and change notifications to stakeholders
- Post-deployment reports and metrics

### Interactions with existing roles
- **Developers**: Coordinate code freeze, review PRs, ensure CI/CD pipeline health
- **Product Managers**: Align on feature readiness and release priorities
- **Project Managers**: Sync on release timelines and cross-team dependencies
- **Support Lead**: Brief on changes before release, coordinate announcements
- **Security Lead**: Verify security scans pass before deployment

---

## UX Designer

### Role Summary
UX Designers create user-centered designs that balance usability, accessibility, and business goals. They research user needs, design interfaces, and validate solutions through testing and iteration.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Ensure designs meet accessibility standards (WCAG, ADA)
- Collaborate with Product and Engineering on design feasibility
- Maintain design systems and component libraries
- Validate implementation matches design intent

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support costs
- Ensure design consistency across products

### Typical Communication
- Design reviews and critique sessions
- User research findings and recommendations
- Design specifications and handoff documentation
- Usability test results and iteration plans

### Interactions with existing roles
- **Product Managers**: Collaborate on user needs, feature requirements, and success metrics
- **Developers**: Provide design specs, review implementations, clarify design decisions
- **Project Managers**: Communicate design timelines and dependencies
- **Support Lead**: Gather user feedback and pain points
- **Data Analyst**: Review usage patterns and conversion metrics

---

## Support Lead

### Role Summary
Support Leads ensure customers receive timely, effective assistance while feeding product insights back to the team. They manage escalations, coordinate incident response, and advocate for customer needs.

### Responsibilities
- Triage and resolve customer issues and escalations
- Coordinate incident response with Engineering and Product
- Maintain support documentation and knowledge bases
- Gather and communicate customer feedback and pain points
- Track support metrics (resolution time, satisfaction, ticket volume)
- Participate in release planning and provide customer impact analysis

### Goals
- Maximize customer satisfaction and retention
- Reduce mean time to resolution (MTTR)
- Minimize repeat issues through feedback loops

### Typical Communication
- Daily triage meetings with support team
- Incident notifications and status updates
- Weekly feedback sessions with Product and Engineering
- Customer communication during incidents and releases

### Interactions with existing roles
- **Product Managers**: Share customer feedback and feature requests
- **Developers**: Collaborate on bug triage and reproduction
- **Project Managers**: Report on support impact of new features
- **Release Manager**: Receive release briefings and coordinate announcements
- **Security Lead**: Escalate security-related customer reports

---

## Security Lead

### Role Summary
Security Leads ensure products and processes meet security standards, managing vulnerabilities, threat assessments, and compliance requirements. They embed security into the development lifecycle and coordinate incident response.

### Responsibilities
- Review code and infrastructure for security vulnerabilities
- Manage security scanning tools and vulnerability remediation
- Conduct threat modeling and security assessments
- Ensure compliance with security policies and standards
- Coordinate security incident response and post-mortems
- Provide security training and guidance to teams

### Goals
- Minimize security vulnerabilities and attack surface
- Ensure compliance with security standards and regulations
- Build security awareness and best practices across teams

### Typical Communication
- Security review sessions during planning and code review
- Vulnerability reports and remediation plans
- Incident response coordination and post-mortems
- Security policy updates and training sessions

### Interactions with existing roles
- **Developers**: Review code for security issues, provide secure coding guidance
- **Product Managers**: Assess security risks in feature proposals
- **Project Managers**: Report on security risks and compliance requirements
- **Release Manager**: Approve security scans before deployment
- **Support Lead**: Investigate security-related customer reports

---

## Data Analyst

### Role Summary
Data Analysts transform data into actionable insights that inform product decisions, track performance, and measure success. They design metrics, build dashboards, and analyze patterns to guide strategy and optimization.

### Responsibilities
- Define and track key performance indicators (KPIs)
- Design and build analytics dashboards and reports
- Analyze user behavior and product usage patterns
- Conduct A/B tests and experiments
- Provide data-driven recommendations for product improvements
- Ensure data quality and integrity

### Goals
- Enable data-driven decision making across teams
- Measure and improve product success metrics
- Identify opportunities for optimization and growth

### Typical Communication
- Weekly metrics reviews with Product and Engineering
- Experiment results and recommendations
- Dashboard demos and documentation
- Ad-hoc analysis requests and findings

### Interactions with existing roles
- **Product Managers**: Define success metrics, analyze feature impact
- **Developers**: Specify instrumentation requirements, validate data accuracy
- **Project Managers**: Provide metrics for project tracking and retrospectives
- **UX Designer**: Share usage patterns and user journey insights
- **Support Lead**: Analyze support trends and identify product issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

