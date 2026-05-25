# OctoAcme Stakeholder Engagement Checklist

## Purpose
Ensure all relevant personas and stakeholders are engaged at the right time in the project lifecycle to minimize surprises, reduce rework, and accelerate delivery.

## When to Use
During project initiation, planning, execution, and release phases. Review and update at each major milestone.

## Pre-Project Initiation
- [ ] Identify all affected teams and personas (see octoacme-roles-and-personas.md)
- [ ] Map stakeholder interests, dependencies, and communication preferences
- [ ] Schedule kickoff meeting with key stakeholders
- [ ] Clarify decision-making authority and approval paths

## During Project Planning
- [ ] Engage Product Manager to define acceptance criteria and success metrics
- [ ] Engage UX Designer to validate user experience and usability requirements
- [ ] Engage QA Lead to scope testing approach and acceptance criteria
- [ ] Engage DevOps Engineer to identify infrastructure and deployment requirements
- [ ] Engage Security Lead to conduct initial threat modeling and identify security requirements
- [ ] Engage Customer Success Manager to understand customer impact and communication needs
- [ ] Review dependencies and escalation paths with all parties
- [ ] Confirm resource availability and timeline feasibility with each team

## During Execution
- [ ] Developers commit to and communicate progress on acceptance criteria
- [ ] UX Designer provides design assets and reviews implementation for fidelity
- [ ] QA Engineer reviews test plans and validates acceptance criteria before testing
- [ ] DevOps Engineer provides test environments and CI/CD pipeline support
- [ ] Security Lead reviews code for vulnerabilities and architecture decisions
- [ ] Product Manager validates feature direction and prioritization with customers
- [ ] Project Manager escalates blockers and risks to appropriate stakeholders
- [ ] Customer Success Manager communicates progress and timelines to customers

## Pre-Release / Deployment
- [ ] Product Manager confirms feature completeness against roadmap and customer needs
- [ ] QA Engineer certifies acceptance criteria met and quality gates passed
- [ ] DevOps Engineer validates deployment readiness and rollback plan
- [ ] Security Lead signs off on security review and incident readiness
- [ ] Customer Success Manager prepares customer communication and training materials
- [ ] Project Manager coordinates release timing and stakeholder announcements

## Post-Release / Retrospective
- [ ] Gather feedback from all personas (developers, QA, security, ops, customers, etc.)
- [ ] Capture lessons learned and action items with clear owners
- [ ] Security Lead conducts post-incident review if applicable
- [ ] Customer Success Manager measures customer satisfaction and business impact
- [ ] Product Manager analyzes adoption metrics and feature usage
- [ ] Update process docs based on retrospective findings

## Communication Cadence by Persona
| Persona | Frequency | Forum | Owner |
|---------|-----------|-------|-------|
| Developers | Daily | Standup, Slack | Project Manager |
| Product Manager | Weekly | Sync, roadmap reviews | Project Manager |
| QA Engineer | Daily | Standup, test status | QA Lead |
| UX Designer | Weekly | Design reviews | Product Manager |
| DevOps Engineer | 2x weekly | Ops sync, deployment prep | DevOps Lead |
| Security Lead | Weekly | Security reviews, risk register | Project Manager |
| Customer Success Manager | Weekly | Customer feedback, impact metrics | Product Manager |
| Sponsors/Stakeholders | Bi-weekly/Monthly | Status updates, milestone reviews | Project Manager |

## Escalation and Issue Resolution
- **Level 1 (Team)**: Issue identified and triage in daily standup or team Slack
- **Level 2 (Department)**: PM escalates to Product Lead and dependent team leads
- **Level 3 (Executive)**: Product Lead or PM escalates to Sponsor for business impact decisions
- **Security/Incident**: Security Lead triggers incident response protocol immediately

## Template: Stakeholder Engagement Plan
Use this template during project initiation to document engagement strategy:

```
Project: [Project Name]
Project Manager: [Name]
Date: [Date]

| Persona | Role | Engagement Phase | Frequency | Contact | Notes |
|---------|------|------------------|-----------|---------|-------|
| [Name] | Developer | Planning, Execution | Daily standup | Slack | Lead dev on feature X |
| [Name] | Product Manager | Planning, Review | Weekly sync | Calendar invite | Owns roadmap priority |
| [Name] | QA Engineer | Planning, Execution, Release | Daily standup + weekly review | Slack | QA lead for acceptance |
| [Name] | UX Designer | Planning, Execution, Review | Weekly design review | Figma + calendar | Provides specs and assets |
| [Name] | DevOps Engineer | Planning, Execution, Release | Bi-weekly ops sync | Slack | Manages CI/CD and infra |
| [Name] | Security Lead | Planning, Execution, Release | Weekly security review | Calendar invite | Threat model and risk review |
| [Name] | Customer Success Manager | Initiation, Release, Retrospective | Weekly customer updates | Email + calendar | Customer voice and feedback |
| [Name] | [Sponsor/Stakeholder] | Initiation, Release | Bi-weekly updates | Email + calendar | Business decision maker |
```

---

## Related Documents
- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)
