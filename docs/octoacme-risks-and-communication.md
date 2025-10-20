# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

**Note**: Security risks should be reviewed with the **Security Lead** and customer-impacting risks with the **Support Lead**.

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Support Lead** communicates customer-facing changes and known issues
- **Data Analyst** provides metrics and impact analysis in stakeholder updates

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary (coordinated by **Release Manager** or on-call engineer)
- Actions being taken
- Customer impact assessment (**Support Lead**)
- Expected timeline
- Security implications reviewed (**Security Lead** if applicable)
- Post-incident blameless retrospective scheduled (**Project Manager**)
- Metrics and impact analysis (**Data Analyst**)

## Escalation Paths

### General Escalations
- Level 1: Team-level triage (Developer, PM)
- Level 2: **Project Manager** -> Product Lead
- Level 3: Product Lead -> Sponsor
- Cross-team dependencies: **Project Manager** coordinates with peer teams

### Security Incidents
- Immediate: Notify **Security Lead** and Security on-call
- Follow security incident runbook
- **Security Lead** coordinates with legal/compliance if needed
- **Support Lead** handles customer communications per security guidance

### Customer-impacting Issues
- Immediate: **Support Lead** assesses severity and customer impact
- Critical: Escalate to **Project Manager** and Product Lead
- **Release Manager** coordinates technical resolution
- **Support Lead** manages customer communications

### Data/Privacy Incidents
- Immediate: Notify **Security Lead** and Data Protection Officer
- **Data Analyst** assesses data exposure scope
- Follow data breach notification procedures
