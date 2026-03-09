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

## QA / Testing

### Role Summary
QA engineers validate that features meet acceptance criteria, quality standards, and user expectations before release. They own test planning, test execution, and defect tracking.

### Responsibilities
- Define and execute test plans (unit, integration, end-to-end, regression)
- Track and report defects with clear reproduction steps
- Verify acceptance criteria and coordinate sign-off with the PM
- Participate in sprint planning to surface testability concerns early
- Support smoke tests and post-release verification

### Goals
- Prevent regressions and defects from reaching production
- Provide clear and timely quality signals to the team
- Continuously improve test coverage and automation

### Typical Communication
- Defect reports and test summary updates
- Collaboration with Developers on bug triage and fix verification
- Pre-release sign-off with PM and Release Manager

---

## Release Manager

### Role Summary
The Release Manager drives release planning, coordinates cutover activities, and ensures smooth, repeatable deployments. They serve as the central point of coordination across teams when a release is imminent.

### Responsibilities
- Own and maintain the release plan, schedule, and cutover checklist
- Coordinate go/no-go decisions with PM, PdM, QA, and Documentation Lead
- Communicate release status and timelines to stakeholders
- Ensure release notes, rollback plans, and smoke tests are in place before deployment
- Facilitate post-release retrospectives focused on deployment quality

### Goals
- Reduce release risk through consistent process and clear checklists
- Ensure all stakeholders are informed and aligned before and after each release
- Drive continuous improvement of the release process

### Typical Communication
- Release planning meetings and cutover calls with PM, PdM, Developers, QA, and Documentation Lead
- Pre-release go/no-go confirmation messages
- Post-release announcements and incident escalations if needed

---

## Documentation Lead

### Role Summary
The Documentation Lead ensures that process documents, user guides, and release notes are accurate, complete, and accessible. They maintain the quality and consistency of all project documentation.

### Responsibilities
- Review and update process documents when roles, workflows, or tooling change
- Collaborate with Developers and QA to document features and APIs
- Ensure release notes are drafted, reviewed, and published for every release
- Maintain a documentation standards guide and template library
- Identify and close documentation gaps identified during retrospectives

### Goals
- Make documentation a reliable source of truth for the team and stakeholders
- Reduce onboarding time by keeping docs current and well-organized
- Enable self-service by ensuring docs are searchable and clearly written

### Typical Communication
- Sync with PM before releases to confirm release notes are ready
- Coordinate with Developers and QA for technical accuracy reviews
- Publish documentation updates alongside feature releases

---

## DevOps Engineer

### Role Summary
The DevOps Engineer owns the CI/CD pipeline, automation, and infrastructure reliability. They partner closely with Developers to enable fast, safe delivery and with the Security Champion to embed security controls into the pipeline.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment infrastructure
- Automate testing, security scanning, and deployment processes
- Monitor system health, reliability, and performance in production
- Manage infrastructure-as-code and environment consistency
- Support incident response with tooling for rollback, logging, and observability

### Goals
- Enable the team to ship frequently with confidence and low risk
- Minimize manual toil through automation
- Maintain high availability and fast mean time to recovery (MTTR)

### Typical Communication
- Collaborate with Developers on pipeline requirements and deployment strategies
- Coordinate with Security Champion on scanning and compliance tooling
- Share infrastructure status and incident updates with PM and stakeholders

---

## Security Champion

### Role Summary
The Security Champion drives proactive risk mitigation and ensures security best practices are embedded throughout the project lifecycle. They act as the team's subject-matter expert on security topics and serve as a liaison to any dedicated security team.

### Responsibilities
- Conduct or coordinate security reviews for new features, architecture changes, and third-party integrations
- Maintain the threat model and update it as the system evolves
- Partner with DevOps to integrate security scanning into CI/CD
- Triage and track security-related risks in the Risk Register
- Run or facilitate security-focused retrospective items and training

### Goals
- Identify and mitigate security risks before they reach production
- Foster a security-aware culture within the team
- Ensure compliance with relevant security standards and policies

### Typical Communication
- Security review sessions with Developers and DevOps at key milestones
- Risk escalation to PM when a high-impact vulnerability is identified
- Periodic security status updates shared with PdM and stakeholders

---

## Customer Experience Advocate

### Role Summary
The Customer Experience Advocate represents the voice of the customer throughout the project lifecycle. They surface customer feedback, usability insights, and satisfaction signals to ensure product decisions remain customer-centric.

### Responsibilities
- Gather and synthesize customer feedback from support channels, surveys, and user research
- Present customer insights and pain points during backlog grooming and planning sessions
- Collaborate with PM and PdM to prioritize features that address real customer needs
- Work with QA to validate that UX changes meet usability standards
- Track customer satisfaction metrics and share trends with the team

### Goals
- Ensure the product solves real customer problems with a high-quality user experience
- Keep the customer perspective visible in every stage of planning and delivery
- Reduce support escalations by proactively identifying usability gaps

### Typical Communication
- Regular feedback summaries shared with PM and PdM
- Participation in sprint reviews and backlog refinement to highlight customer impact
- Coordination with QA on acceptance testing from a user perspective

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When assigning work or building checklists, reference the role summaries above to identify the right owner for each task.

