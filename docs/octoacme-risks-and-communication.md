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
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

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

## Escalation Paths
- **Team-level** (Low/Medium risk): Triage in daily standup; Owner documents mitigation in Risk Register.
- **PM level** (Medium/High risk): PM escalates to Product Lead and dependent teams; update stakeholders within 24 hours.
- **Sponsor level** (High/Critical risk): PM escalates to Sponsor; blocker must have a mitigation or decision within 48 hours.
- **Security incidents**: Notify Security Champion and follow the security incident runbook; loop in DevOps Engineer for infrastructure issues; escalate to PM and Sponsor if customer data or compliance is at risk.
- **Release-blocking issues**: Release Manager coordinates go/no-go decision with PM, QA, and Security Champion before proceeding.

## Risk Ownership
| Role | Responsibility |
|---|---|
| Project Manager (PM) | Owns Risk Register; facilitates weekly risk review |
| Security Champion | Owns security and compliance risks |
| DevOps Engineer | Owns infrastructure and pipeline risks |
| Release Manager | Owns release-related risks and go/no-go decisions |
| Developers | Surface technical risks during planning and daily standups |
