# Role-Based Checklists

These checklists ensure that key handoff points in the project lifecycle are consistently executed. Each item identifies the primary role(s) responsible for completing it.

> **How to use**: Copy the relevant checklist into your sprint ticket or release document. Check off items as they are completed. Raise blockers as issues or comments on the ticket.

---

## Release Handoff Checklist

Use this checklist before every production release to confirm that all teams are ready and that the handoff is complete.

### Pre-Release Preparation
- [ ] **Release Engineer**: Deployment runbook is written and reviewed.
- [ ] **Release Engineer**: Rollback procedure is documented and tested in staging.
- [ ] **Release Engineer**: CI/CD pipeline passes all stages (build, test, security scan).
- [ ] **QA Engineer**: Full regression test suite has been executed and passed.
- [ ] **QA Engineer**: All P1 and P2 bugs are resolved or have an approved deferral.
- [ ] **QA Engineer**: Smoke test script is ready for post-deployment verification.
- [ ] **PM**: Go/no-go criteria are defined and agreed with PdM and Release Engineer.
- [ ] **PM**: Release schedule communicated to all stakeholders.
- [ ] **Support**: Release notes reviewed and support FAQ updated.
- [ ] **Support**: Support team briefed on new features, known issues, and escalation paths.

### Release Execution
- [ ] **Release Engineer**: Deployment initiated in production following the runbook.
- [ ] **QA Engineer**: Smoke tests executed against production environment.
- [ ] **Release Engineer**: Deployment health metrics checked (error rates, latency).
- [ ] **PM**: Go/no-go decision confirmed post-deployment.

### Post-Release
- [ ] **Release Engineer**: Deployment retrospective notes captured.
- [ ] **Support**: Customer-reported issues triaged and routed to the appropriate team.
- [ ] **PM**: Release closure email / announcement sent to stakeholders.
- [ ] **Analytics / Data Engineer**: Analytics instrumentation validated in production.

---

## Design Handoff Checklist

Use this checklist when UX Designer hands off designs to the Development team for implementation.

### Before Handoff (UX Designer)
- [ ] **UX Designer**: All screens and states (empty, loading, error, success) are designed and annotated.
- [ ] **UX Designer**: Design assets exported and accessible in the agreed tool (e.g., Figma).
- [ ] **UX Designer**: Interaction and animation specifications documented.
- [ ] **UX Designer**: Responsive/adaptive breakpoints defined for all relevant screen sizes.
- [ ] **UX Designer**: Accessibility annotations added (color contrast, focus order, ARIA roles).
- [ ] **Accessibility Advocate**: Design reviewed for WCAG 2.1 AA compliance.

### PdM Review
- [ ] **PdM**: Design reviewed against acceptance criteria and user stories.
- [ ] **PdM**: Any open design decisions documented and resolved before handoff.
- [ ] **PdM**: Final design approved and version locked for implementation.

### Handoff to Development
- [ ] **UX Designer**: Design walkthrough session scheduled with Developers.
- [ ] **Developer**: Developers confirm they have access to all assets and specs.
- [ ] **Developer**: Implementation feasibility confirmed (no blocking constraints).
- [ ] **UX Designer**: Design review checkpoint scheduled (mid-implementation) to verify fidelity.

### Post-Implementation
- [ ] **UX Designer**: Implemented feature reviewed against design specs.
- [ ] **Accessibility Advocate**: Accessibility verification completed on implemented screens.
- [ ] **UX Designer**: Any deviations from design documented and approved by PdM.

---

## Documentation Handoff Checklist

Use this checklist to ensure documentation is completed and handed off before a feature release.

### Planning (Technical Writer + PdM)
- [ ] **Technical Writer**: Documentation scope agreed with PdM (user guide, API docs, release notes, runbook).
- [ ] **PdM**: Feature context and key user journeys shared with Technical Writer.
- [ ] **Technical Writer**: Documentation work items added to the project backlog and scheduled.

### Drafting and Review
- [ ] **Technical Writer**: First draft of all required documentation completed.
- [ ] **Developer**: Technical accuracy review completed and feedback provided.
- [ ] **PdM**: Content reviewed for completeness against acceptance criteria.
- [ ] **Support**: Draft reviewed for clarity and usability from a customer perspective.
- [ ] **Technical Writer**: All review feedback incorporated and final draft ready.

### Pre-Release
- [ ] **Technical Writer**: Documentation published (or staged) and links verified.
- [ ] **Technical Writer**: Release notes written and shared with PM and PdM for approval.
- [ ] **PM**: Release notes approved and included in release announcement.
- [ ] **Support**: Support documentation (FAQ, runbook) reviewed and ready to publish.

### Post-Release
- [ ] **Technical Writer**: Documentation URLs included in release announcement.
- [ ] **Support**: Customer feedback on documentation collected and shared with Technical Writer.
- [ ] **Technical Writer**: Post-release documentation issues tracked and prioritised for the next sprint.

---

## Related Documents
- [Roles & Personas](../octoacme-roles-and-personas.md)
- [Role Interactions & RACI Matrix](../octoacme-role-interactions.md)
