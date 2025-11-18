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

## Risk Lifecycle
- Identify: during planning and ongoing execution
  - **Security Lead**: Identifies security and compliance risks
  - **Operations Manager**: Identifies infrastructure and operational risks
  - **Data Analyst**: Identifies data quality and analytics risks
- Assess: estimate impact and likelihood
  - Cross-functional input from all relevant roles
- Mitigate: reduced via actions, contingency plans
  - Role-specific mitigation owned by respective leads
- Monitor: review at weekly syncs and update status
  - **Project Manager**: Tracks and reports on all risks
  - **Support Lead**: Monitors customer-impacting risks

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, operations, security)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Support Lead**: Coordinates customer-facing communications and manages support team awareness
- **Data Analyst**: Provides metrics and insights to inform stakeholder updates
- **Operations Manager**: Communicates infrastructure and system health status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled
- **Operations Manager**: Leads technical incident response
- **Support Lead**: Manages customer communications during incidents
- **Security Lead**: Leads security incident response and forensics

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- **Security Lead**: Manages security escalation path and compliance notifications
- **Operations Manager**: Handles infrastructure and availability escalations
- **Support Lead**: Escalates customer-critical issues to product and engineering teams
