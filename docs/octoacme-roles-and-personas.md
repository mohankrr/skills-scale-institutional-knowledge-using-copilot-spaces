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

### Interactions
- **QA Engineer**: Share implementation details, support test environment setup, and respond to bug reports promptly.
- **UX Designer**: Receive design assets and specs during design handoff; provide feasibility feedback early in design cycles.
- **Technical Writer**: Supply context for feature documentation; review drafts for technical accuracy.
- **Release Engineer**: Coordinate deployment steps, environment configs, and release checklists.
- **Security Reviewer**: Incorporate security recommendations from code review and threat-modelling sessions.
- **Accessibility Advocate**: Apply accessibility guidance during implementation and address flagged issues before release.

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

### Interactions
- **UX Designer**: Co-create user flows, review wireframes, and validate designs against success metrics.
- **Technical Writer**: Provide feature context and review documentation drafts before release.
- **Analytics / Data Engineer**: Define tracking requirements and validate that metrics are being captured correctly.
- **Support / Customer Success Representative**: Gather customer feedback to inform backlog prioritization.
- **QA Engineer**: Write and review acceptance criteria collaboratively; sign off on quality gates.

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

### Interactions
- **Release Engineer**: Align on release timelines, go/no-go criteria, and deployment runbooks.
- **Technical Writer**: Track documentation deliverables as part of the Definition of Done.
- **Support / Customer Success Representative**: Keep support teams informed of upcoming changes and known issues.
- **Security Reviewer**: Escalate security findings that affect scope, schedule, or release readiness.
- **Analytics / Data Engineer**: Ensure instrumentation tasks are scoped and tracked in the project plan.

---

## UX Designer

### Role Summary
UX Designers plan, design, and validate the user experience of products. They ensure that interfaces are intuitive, accessible, and aligned with user needs and business goals.

### Responsibilities
- Conduct user research and synthesize insights into design requirements
- Create wireframes, prototypes, and high-fidelity design assets
- Facilitate design reviews and usability tests
- Collaborate with Product Managers on user stories and acceptance criteria
- Ensure designs meet accessibility standards
- Hand off final specs and assets to Developers

### Goals
- Deliver designs that meet user needs and reduce friction
- Promote accessibility and inclusive design practices
- Shorten feedback loops between design and development

### Typical Communication / Interactions
- Design reviews and prototype walkthroughs with PdM and Developers
- Handoff documentation (e.g., Figma specs) shared with Developer team
- Accessibility check-ins with Accessibility Advocate
- Usability test sessions with Support / Customer Success Representative

---

## QA Engineer

### Role Summary
QA Engineers own the quality assurance strategy for features and releases. They design and execute test plans, drive automation, and act as the quality gate before features reach production.

### Responsibilities
- Design and maintain test plans and test cases aligned with acceptance criteria
- Execute manual and automated functional, regression, and integration tests
- Report, triage, and verify fixes for bugs and defects
- Collaborate with Developers and PdMs to define Definition of Done
- Contribute to test automation frameworks and CI/CD pipelines
- Run smoke and sanity tests for releases

### Goals
- Prevent defects from reaching production
- Increase test coverage and automation ratio
- Provide rapid quality feedback to the development team

### Typical Communication / Interactions
- Sprint planning and backlog grooming with PdM and Developers to clarify acceptance criteria
- Bug tracking via issue tracker with Developers
- Release sign-off coordination with Release Engineer and PM
- Escalation of critical defects to Project Manager

---

## Technical Writer

### Role Summary
Technical Writers produce and maintain user-facing and internal documentation. They translate complex technical topics into clear, accurate content that supports users, developers, and operators.

### Responsibilities
- Write and maintain user guides, API docs, release notes, and runbooks
- Collaborate with PdMs and Developers to capture feature details
- Review and edit draft documentation from engineers
- Maintain the documentation style guide and templates
- Track documentation work items in the project backlog

### Goals
- Ensure documentation is accurate, up-to-date, and discoverable
- Reduce support burden by improving self-service content
- Simplify onboarding for new team members and end users

### Typical Communication / Interactions
- Regular syncs with PdM to review upcoming features and documentation scope
- Review cycles with Developers to verify technical accuracy
- Coordination with Support / Customer Success Representative to identify documentation gaps
- Documentation handoff to Support before release

---

## Release Engineer

### Role Summary
Release Engineers own the release pipeline, deployment process, and environment management. They ensure that software is safely and reliably delivered to production.

### Responsibilities
- Maintain CI/CD pipelines and deployment tooling
- Plan and execute release activities per the release schedule
- Coordinate go/no-go decisions with PM, QA, and PdM
- Manage rollback procedures and hotfix processes
- Document deployment runbooks and release notes

### Goals
- Achieve zero-surprise releases with clear rollback paths
- Reduce deployment lead time and failure rate
- Maintain stable and reproducible release environments

### Typical Communication / Interactions
- Pre-release syncs with PM and QA Engineer to confirm readiness
- Deployment briefings with Developers
- Incident handoff to Support / Customer Success Representative and Security Reviewer when issues arise
- Post-release verification sign-off with QA

---

## Security Reviewer

### Role Summary
Security Reviewers assess features, architecture, and code changes for security vulnerabilities and compliance risks. They provide guidance and approve changes from a security standpoint.

### Responsibilities
- Conduct threat modelling and security design reviews
- Perform or coordinate code security audits and dependency scanning
- Define and enforce security acceptance criteria for features
- Triage and prioritize security findings with Developers
- Maintain security checklists and best practice guidance

### Goals
- Prevent security vulnerabilities from reaching production
- Build a security-aware engineering culture
- Ensure compliance with relevant standards and regulations

### Typical Communication / Interactions
- Security review sessions with Developers and Release Engineer during feature development
- Risk escalation to Project Manager and PdM when findings affect schedule or scope
- Post-release monitoring review with Analytics / Data Engineer
- Input to release go/no-go decisions with Release Engineer and PM

---

## Support / Customer Success Representative

### Role Summary
Support / Customer Success Representatives serve as the voice of the customer within the project team. They surface real-world usage patterns, manage customer communications, and ensure that releases do not disrupt customer operations.

### Responsibilities
- Relay customer feedback and pain points to PdM and PM
- Review release notes and documentation before publication
- Prepare support runbooks and FAQ updates for new features
- Triage and escalate production incidents from the customer perspective
- Participate in UAT (user acceptance testing) for high-impact features

### Goals
- Minimize customer disruption during releases
- Reduce time-to-resolution for customer-reported issues
- Ensure customers are informed and prepared for changes

### Typical Communication / Interactions
- Regular feedback sessions with PdM to relay customer insights
- Pre-release briefings from PM and Release Engineer
- Documentation review cycles with Technical Writer
- Post-release incident triage with Release Engineer and Security Reviewer

---

## Analytics / Data Engineer

### Role Summary
Analytics / Data Engineers design, build, and validate the instrumentation and data pipelines that power product metrics and business intelligence.

### Responsibilities
- Define tracking requirements with PdM (events, funnels, KPIs)
- Implement and maintain analytics instrumentation in the product
- Build and monitor data pipelines for product and operational metrics
- Validate data quality and alert on anomalies
- Provide data analyses to support decision-making

### Goals
- Ensure reliable, accurate, and timely data for decision-makers
- Accelerate insight generation for PdMs and business stakeholders
- Reduce time-to-data for new features and experiments

### Typical Communication / Interactions
- Instrumentation planning sessions with PdM during feature scoping
- Technical implementation discussions with Developers
- Post-release data validation reviews with PdM and Security Reviewer
- Regular data quality reports shared with Project Manager and stakeholders

---

## Accessibility Advocate

### Role Summary
Accessibility Advocates champion inclusive design and development practices to ensure that products are usable by people of all abilities. They review designs, code, and content for accessibility compliance.

### Responsibilities
- Review design mocks and prototypes for accessibility compliance (WCAG guidelines)
- Audit feature implementations using assistive technologies and automated tools
- Provide accessibility guidance and training to Developers and UX Designers
- Track and prioritize accessibility findings in the project backlog
- Validate fixes before release

### Goals
- Ensure products meet accessibility standards (WCAG 2.1 AA or higher)
- Embed accessibility practices into design and development workflows
- Reduce accessibility debt and prevent new regressions

### Typical Communication / Interactions
- Design review checkpoints with UX Designer
- Code review annotations and accessibility testing results shared with Developers
- Pre-release accessibility sign-off coordinated with QA Engineer and Release Engineer
- Accessibility findings escalated to PM when they block a release

---

## Example Release Scenario

The following scenario illustrates how these personas coordinate during a typical feature release cycle:

1. **Authoring acceptance criteria**: PdM writes feature requirements and acceptance criteria in collaboration with QA Engineer and UX Designer. Accessibility Advocate reviews criteria to ensure accessibility requirements are included.

2. **Design handoff**: UX Designer finalises wireframes and high-fidelity mocks, shares them via Figma with Developers. Accessibility Advocate reviews designs before handoff. PdM approves final designs.

3. **Development and security review**: Developers implement the feature following the design specs. Security Reviewer conducts a threat model review and flags any concerns. Analytics / Data Engineer instruments the required events.

4. **Testing**: QA Engineer executes the test plan, running functional, regression, and accessibility-assisted checks. Bugs are filed and resolved with Developers. Release Engineer validates the deployment pipeline in a staging environment.

5. **Release verification**: Release Engineer runs the deployment runbook and executes smoke tests with QA Engineer. Go/no-go decision is made by PM, PdM, and Release Engineer. Support / Customer Success Representative reviews the release notes and prepares the support FAQ.

6. **Post-release support**: Support / Customer Success Representative monitors customer feedback and routes issues to the relevant team. Analytics / Data Engineer validates that instrumentation is firing correctly. Project Manager leads a retrospective to capture learnings.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Interactions & RACI Matrix](octoacme-role-interactions.md) for guidance on who is responsible, accountable, consulted, and informed for common project activities.
- See [Role-Based Checklists](checklists/role-based-checklists.md) for handoff checklists covering release, design, and documentation workflows.

