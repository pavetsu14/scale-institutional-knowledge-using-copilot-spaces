# OctoAcme — Team Member Onboarding Checklist

## Purpose
Help new team members get up to speed quickly with OctoAcme's project management processes, tooling, and team norms.

## When to use
Use this checklist whenever a new team member joins the project. The PM or designated onboarding buddy should walk through it with the new team member during their first week.

---

## Week 1: Orientation

### People & Context
- [ ] Introduce new team member to PM, PdM, and key stakeholders — Owner: PM
- [ ] Confirm the new team member's role and responsibilities using [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)
- [ ] Schedule 1:1s with immediate collaborators (e.g., Developers, QA, Release Manager, Security Champion as applicable)

### Documentation & Process
- [ ] Share the [project management overview](octoacme-project-management-overview.md) and walk through the lifecycle
- [ ] Provide access to the project board (GitHub Projects or equivalent)
- [ ] Share links to all relevant process docs in the `docs/` folder
- [ ] Confirm the new team member has read and understood the [roles and personas guide](octoacme-roles-and-personas.md)

### Tooling & Access
- [ ] Grant repository access with appropriate permissions — Owner: PM or DevOps Engineer
- [ ] Set up CI/CD access if relevant (DevOps Engineer to assist)
- [ ] Add to team communication channels (Slack, Teams, or equivalent)
- [ ] Add to recurring meetings: standup, planning, retrospective, weekly sync

---

## Week 2: Hands-on Ramp-up

### Process Participation
- [ ] Attend first sprint planning or backlog grooming session
- [ ] Review an open or recent PR to understand code review norms
- [ ] Review the current Risk Register and understand any active risks
- [ ] Attend or review a recent retrospective to understand team improvement areas

### Role-specific Onboarding
Complete the relevant section(s) below based on the new team member's role:

#### Developer
- [ ] Complete local development environment setup
- [ ] Submit a first small PR (e.g., a bug fix or documentation update) to learn the PR workflow
- [ ] Review the Definition of Done and coding standards

#### QA / Testing
- [ ] Review the current test plan and test suite
- [ ] Run existing automated tests locally
- [ ] Shadow a developer during a QA handoff

#### Release Manager
- [ ] Review the [release and deployment guide](octoacme-release-and-deployment.md)
- [ ] Shadow or debrief on the most recent release process
- [ ] Confirm access to deployment tooling and environments

#### Documentation Lead
- [ ] Audit the `docs/` folder for any out-of-date or missing documents
- [ ] Review the release notes template in the [release guide](octoacme-release-and-deployment.md)
- [ ] Coordinate with PM to understand the documentation calendar

#### DevOps Engineer
- [ ] Review CI/CD pipeline configuration and deployment workflows
- [ ] Confirm monitoring and alerting setup
- [ ] Coordinate with Security Champion on scanning tooling

#### Security Champion
- [ ] Review the threat model (if one exists) or schedule a session to create one
- [ ] Confirm security scanning is integrated in CI with DevOps Engineer
- [ ] Review the security escalation path in [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)

#### Customer Experience Advocate
- [ ] Review existing customer feedback channels and sources
- [ ] Attend a backlog grooming session to understand how customer insights are currently surfaced
- [ ] Meet with PM and PdM to align on how customer data influences prioritization

---

## Onboarding Sign-off

| Item | Completed | Date | Notes |
|---|---|---|---|
| Role confirmed and responsibilities understood | | | |
| Process docs reviewed | | | |
| Tooling access granted | | | |
| First meeting cycle attended | | | |
| Role-specific ramp-up complete | | | |

**PM / Onboarding Buddy sign-off:** ____________________  
**New team member sign-off:** ____________________  
**Date:** ____________________
