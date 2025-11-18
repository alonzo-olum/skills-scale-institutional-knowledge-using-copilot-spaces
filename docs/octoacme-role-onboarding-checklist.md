# OctoAcme — Role Onboarding Checklist

## Purpose
This document provides templates and checklists to help teams assign, onboard, and clarify responsibilities for new roles joining a project. Use this to ensure smooth role integration and clear accountability.

---

## General Role Onboarding Checklist

When adding any new role to a project, complete the following:

- [ ] **Define scope and expectations** — Review the role description in [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) and clarify specific responsibilities for this project
- [ ] **Identify stakeholders** — Determine who the role will interact with regularly (PM, developers, other roles)
- [ ] **Grant access** — Provide necessary tool access (repositories, project boards, monitoring dashboards, communication channels)
- [ ] **Share context** — Review project one-pager, current status, and key documentation (initiation, planning, risk register)
- [ ] **Establish communication rhythm** — Add to relevant meetings (standups, planning, retrospectives) and communication channels
- [ ] **Set goals and success metrics** — Align on role-specific goals and how success will be measured
- [ ] **Schedule check-ins** — Plan regular 1:1s or syncs to address questions and provide feedback
- [ ] **Document role assignment** — Update project documentation to reflect the role and owner

---

## Role-Specific Onboarding Templates

### Operations Manager Onboarding

**Context to share:**
- Current infrastructure setup and architecture diagrams
- Monitoring and alerting systems in use
- Existing runbooks and incident response procedures
- Deployment pipeline and release schedule
- Service level objectives (SLOs) and availability targets

**Access required:**
- Production and staging environment access
- Monitoring dashboards (logs, metrics, alerts)
- CI/CD pipeline configuration
- Incident management tools
- Infrastructure-as-code repositories

**Key deliverables (first 30 days):**
- [ ] Review and update infrastructure documentation
- [ ] Validate monitoring coverage and alerting thresholds
- [ ] Document or improve deployment runbooks
- [ ] Establish on-call rotation (if applicable)
- [ ] Conduct infrastructure capacity review

**Success metrics:**
- System uptime and availability
- Deployment frequency and success rate
- Mean time to detect (MTTD) and recover (MTTR) from incidents
- Infrastructure cost optimization

---

### UX/UI Designer Onboarding

**Context to share:**
- Product vision and user personas
- Current design system and brand guidelines
- User research findings and feedback
- Accessibility requirements and standards
- Analytics and usage data

**Access required:**
- Design tools (Figma, Sketch, Adobe XD)
- User research and testing platforms
- Analytics dashboards
- Prototyping and collaboration tools
- Design system repository

**Key deliverables (first 30 days):**
- [ ] Review existing designs and user flows
- [ ] Audit accessibility compliance
- [ ] Create or update design system documentation
- [ ] Conduct stakeholder interviews to understand priorities
- [ ] Establish design review process

**Success metrics:**
- User satisfaction scores (NPS, CSAT)
- Task completion rates and time-on-task
- Accessibility compliance score
- Design consistency across features

---

### Security Lead Onboarding

**Context to share:**
- Security policies and compliance requirements
- Existing security controls and tools
- Previous security assessments and findings
- Incident response plan
- Data classification and handling procedures

**Access required:**
- Security scanning tools (SAST, DAST, SCA)
- Vulnerability management systems
- Audit logs and SIEM tools
- Compliance documentation
- Security incident response channels

**Key deliverables (first 30 days):**
- [ ] Conduct initial security assessment
- [ ] Review and update threat model
- [ ] Validate security scanning coverage
- [ ] Document security baselines and standards
- [ ] Schedule security training for team

**Success metrics:**
- Number of critical/high vulnerabilities (trend toward zero)
- Mean time to remediate security findings
- Compliance audit pass rate
- Security awareness training completion

---

### Data Analyst Onboarding

**Context to share:**
- Product success metrics and KPIs
- Current data sources and analytics tools
- Data governance policies
- Existing dashboards and reports
- Key business questions to answer

**Access required:**
- Analytics platforms (Google Analytics, Amplitude, Mixpanel)
- Data warehouse and BI tools
- Experimentation platforms
- Data pipeline documentation
- Reporting tools (Tableau, Looker, PowerBI)

**Key deliverables (first 30 days):**
- [ ] Audit existing metrics and dashboards
- [ ] Define or validate KPI definitions
- [ ] Create data quality assessment
- [ ] Document key data sources and schemas
- [ ] Establish reporting cadence and templates

**Success metrics:**
- Data quality and accuracy
- Dashboard adoption and usage
- Time to insight for key questions
- Experiment velocity and rigor

---

### Support Lead Onboarding

**Context to share:**
- Product features and roadmap
- Support processes and escalation workflows
- Customer segments and use cases
- Knowledge base and support documentation
- Current support metrics and SLAs

**Access required:**
- Support ticketing system (Zendesk, Intercom, ServiceNow)
- Customer communication channels
- Product documentation and knowledge base
- Customer data and account information (with appropriate permissions)
- Internal communication channels with engineering/product

**Key deliverables (first 30 days):**
- [ ] Review support ticket trends and common issues
- [ ] Audit and update support documentation
- [ ] Establish or refine escalation procedures
- [ ] Create support metrics dashboard
- [ ] Conduct customer feedback analysis

**Success metrics:**
- First response time and resolution time
- Customer satisfaction (CSAT) score
- Support ticket volume and trends
- Knowledge base article usage and effectiveness

---

## Role Assignment Matrix Template

Use this template to document role assignments for your project:

| Role | Name | Start Date | Primary Responsibilities | Key Stakeholders | Success Metrics |
|------|------|------------|-------------------------|------------------|----------------|
| Product Manager | | | | | |
| Project Manager | | | | | |
| Developer | | | | | |
| Operations Manager | | | | | |
| UX/UI Designer | | | | | |
| Security Lead | | | | | |
| Data Analyst | | | | | |
| Support Lead | | | | | |

---

## Cross-Functional RACI Template

Use RACI (Responsible, Accountable, Consulted, Informed) to clarify role interactions:

| Activity | PM | PdM | Dev | Ops Mgr | UX/UI | Security | Data Analyst | Support |
|----------|----|----|-----|---------|-------|----------|--------------|---------|
| Product roadmap | C | A | I | I | C | C | C | C |
| Feature design | C | R | C | I | A | C | I | I |
| Code development | I | I | A/R | C | I | C | I | I |
| Security review | I | I | C | I | I | A/R | I | I |
| Release deployment | I | C | C | A/R | I | C | I | I |
| Incident response | C | C | R | A | I | R | C | R |
| Metrics analysis | C | C | I | C | C | I | A/R | C |
| Customer support | C | C | I | C | C | I | C | A/R |

**Legend:**
- **R** (Responsible): Does the work
- **A** (Accountable): Ultimately answerable; only one A per activity
- **C** (Consulted): Provides input
- **I** (Informed): Kept updated

Customize this template based on your project's specific needs and workflows.

---

## Ongoing Role Management

**Regular check-ins:**
- Review role effectiveness during sprint retrospectives
- Adjust responsibilities as project needs evolve
- Ensure roles have adequate support and resources

**Documentation updates:**
- Keep role assignments current in project documentation
- Update RACI matrix when workflows change
- Share role changes with all stakeholders

**Continuous improvement:**
- Gather feedback from role owners on clarity and effectiveness
- Identify gaps or overlaps in responsibilities
- Refine role definitions based on lessons learned
