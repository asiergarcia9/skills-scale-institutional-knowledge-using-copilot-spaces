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

## QA Engineers

### Role Summary
QA Engineers design and execute test strategies, manage quality gates, and ensure that software meets acceptance criteria and quality standards before release. They act as quality advocates throughout the project lifecycle.

### Responsibilities
- Design comprehensive test plans aligned with acceptance criteria
- Execute manual and automated testing across all phases
- Manage defect triage, prioritization, and closure tracking
- Establish and enforce quality gates before release
- Collaborate on CI/CD test integration and automation
- Identify and report quality risks early

### Goals
- Ensure customer-ready quality and reliability
- Reduce defects reaching production
- Enable fast, confident releases through automation
- Advocate for quality in all project decisions

### Interactions with Other Roles
- **Developers**: Review acceptance criteria together; provide detailed defect reports; collaborate on test automation
- **Product Managers**: Validate feature acceptance criteria; discuss test coverage priorities
- **DevOps Engineers**: Integrate automated tests into CI/CD pipelines; manage test environments
- **UX Designers**: Validate usability and user acceptance criteria

### Typical Communication
- Test plan reviews and defect logs
- Daily standup updates on quality metrics
- Pre-release quality sign-offs

---

## UX Designers

### Role Summary
UX Designers ensure that products are user-centric, intuitive, and accessible. They lead research, prototyping, and design validation to advocate for users throughout the project lifecycle.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, prototypes, and design specifications
- Perform usability testing and iterate based on feedback
- Ensure accessibility and inclusive design standards
- Provide design assets and guidance to developers
- Collaborate on acceptance criteria related to user experience

### Goals
- Deliver intuitive, user-friendly solutions
- Reduce post-launch usability issues and support burden
- Ensure inclusive design accessible to all users
- Drive measurable improvements in user satisfaction

### Interactions with Other Roles
- **Product Managers**: Partner on feature definitions and user research insights
- **Developers**: Provide design specifications and assets; review implementation for design fidelity
- **QA Engineers**: Define usability and accessibility acceptance criteria; participate in user acceptance testing

### Typical Communication
- Design reviews and mockups
- Usability test findings and recommendations
- Design system documentation and guidelines

---

## DevOps Engineers

### Role Summary
DevOps Engineers maintain infrastructure, automate deployment pipelines, and enable reliable, scalable delivery. They drive operational excellence and eliminate toil through automation.

### Responsibilities
- Design and maintain cloud infrastructure and environments
- Automate build, test, and deployment pipelines
- Implement monitoring, logging, and alerting
- Support incident response and post-mortems
- Optimize performance and cost efficiency
- Enable self-service deployment capabilities for teams

### Goals
- Enable fast, reliable, and safe deployments
- Minimize manual operational work (toil)
- Maintain high system availability and performance
- Support rapid iteration and scaling

### Interactions with Other Roles
- **Developers**: Provide CI/CD tooling and support; troubleshoot build failures
- **QA Engineers**: Manage test environments; integrate automated testing into pipelines
- **Project Managers**: Advise on deployment schedules and infrastructure risks
- **Security Lead**: Implement security scanning and compliance controls in pipelines

### Typical Communication
- Infrastructure design reviews
- Deployment runbooks and incident playbooks
- Operational metrics and performance reports

---

## Security Lead

### Role Summary
Security Leads assess project risks, coordinate security reviews, and ensure compliance. They serve as advocates for security practices and incident readiness throughout the project lifecycle.

### Responsibilities
- Conduct threat modeling and security risk assessments
- Define security requirements and acceptance criteria
- Review code and architecture for security vulnerabilities
- Coordinate security testing and penetration testing
- Prepare incident response playbooks and runbooks
- Ensure compliance with relevant standards and regulations
- Lead security incident response and post-mortems

### Goals
- Prevent security breaches and data loss
- Build security into development from the start
- Enable rapid, secure incident response
- Maintain customer trust and regulatory compliance

### Interactions with Other Roles
- **Developers**: Review code for security; advise on secure design patterns
- **Product Managers**: Align on security requirements and data handling policies
- **DevOps Engineers**: Implement security controls in infrastructure and pipelines
- **Project Managers**: Escalate security risks and coordinate incident response

### Typical Communication
- Security design reviews and threat models
- Vulnerability reports and remediation plans
- Incident response alerts and post-mortems

---

## Customer Success Manager

### Role Summary
Customer Success Managers ensure customers achieve desired outcomes and collect feedback to drive continuous improvement. They act as the voice of the customer within the project team.

### Responsibilities
- Ensure successful customer adoption and onboarding
- Collect and prioritize customer feedback
- Identify and escalate customer issues and blockers
- Measure customer satisfaction and business outcomes
- Advocate for customer needs in prioritization discussions
- Support post-launch customer communication and training

### Goals
- Maximize customer value realization and ROI
- Reduce churn and support costs through proactive engagement
- Feed customer insights into product direction
- Build long-term customer relationships and advocacy

### Interactions with Other Roles
- **Product Managers**: Channel customer feedback into prioritization; validate feature fit
- **Project Managers**: Communicate release timelines and features to customers
- **Developers**: Escalate complex customer issues; provide context on customer use cases
- **Support Teams**: Bridge product team and customer support with insights and escalations

### Typical Communication
- Customer feedback summaries and requests
- Customer success metrics and business impact reports
- Post-launch customer communication plans

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning projects, ensure all relevant personas are engaged at appropriate stages.
- Use the interaction sections to clarify communication and collaboration touchpoints.
