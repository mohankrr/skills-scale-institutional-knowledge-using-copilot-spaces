# OctoAcme Role Interactions & RACI Matrix

This document provides a practical RACI-style matrix and guidance for deciding who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for common project activities.

---

## RACI Key

| Code | Meaning |
|------|---------|
| **R** | **Responsible** – does the work |
| **A** | **Accountable** – owns the outcome; approves the result |
| **C** | **Consulted** – provides input before/during the activity |
| **I** | **Informed** – notified of progress or outcome |

---

## Role Abbreviations

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developer |
| QA | QA Engineer |
| UX | UX Designer |
| TW | Technical Writer |
| RE | Release Engineer |
| SR | Security Reviewer |
| Sup | Support / Customer Success Representative |
| ADE | Analytics / Data Engineer |
| AA | Accessibility Advocate |

---

## RACI Matrix

| Activity | PM | PdM | Dev | QA | UX | TW | RE | SR | Sup | ADE | AA |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Define success metrics | C | A | C | C | C | I | I | I | C | R | I |
| Write acceptance criteria | C | A | R | R | C | I | I | C | C | C | C |
| Approve release (go/no-go decision) | A | C | I | C | I | I | R | C | C | I | C |
| Run smoke tests | I | I | C | R | I | I | A | I | I | I | C |
| Triage production incident | A | C | R | C | I | I | R | C | R | C | I |
| Update user docs | C | C | C | I | I | A/R | I | I | C | I | I |
| Run analytics validation | I | A | C | I | I | I | I | C | I | R | I |
| Design handoff | I | A | C | I | R | I | I | I | I | I | C |
| Security design review | C | C | R | C | C | I | C | A/R | I | I | I |
| Accessibility audit | C | C | C | C | R | I | I | I | I | I | A/R |

---

## How to Use This Matrix

### Getting started
1. Copy this table into your project charter or project wiki.
2. Replace the generic roles with the actual names of individuals on your team.
3. Review the matrix during kickoff to confirm everyone understands their role in each activity.

> **Note on "Approve release"**: The Project Manager (PM) is Accountable for the go/no-go business decision, while the Release Engineer (RE) is Responsible for executing the technical deployment steps. If your team combines these roles, assign A/R to the single person who covers both.

### Rules of thumb
- **Only one person should be Accountable (A)** for any given activity. If you have two, decide who the final decision-maker is.
- **Responsible (R) can be shared** across multiple people when the work is collaborative (e.g., joint effort between Dev and QA on writing tests).
- **Consult sparingly.** If everyone is Consulted on everything, it creates noise. Reserve C for roles whose input genuinely changes the output.
- **Informed is lightweight.** Use async channels (Slack, email) rather than meetings for I roles.

### Adapting to team size

| Team size | Guidance |
|---|---|
| Small (< 5 people) | Roles may be combined. One person can hold Dev + QA or PdM + PM. Update the matrix to reflect the actual people, not titles. |
| Medium (5–15 people) | Use the matrix as-is; assign named individuals to each role column. |
| Large (15+ / multi-team) | Split the matrix by workstream or squad. Each squad maintains its own RACI for its activities. |

### Adapting to project criticality

| Criticality | Guidance |
|---|---|
| High (customer-facing, regulated) | Security Reviewer and Accessibility Advocate should be Consulted or Accountable on more activities. Add additional rows for compliance checkpoints. |
| Medium (internal tools) | Simplify; merge SR/AA rows into a single "Quality & Compliance" role if the team is small. |
| Low (experiments, prototypes) | Use a lighter version with only the core rows: define metrics, write acceptance criteria, approve release. |

### Example
> The team is preparing to release a new checkout flow. The PdM is Accountable for defining success metrics. The Dev team is Responsible for writing the implementation. The QA Engineer is Responsible for running smoke tests, and the Release Engineer is Accountable for approving the release deployment. The Support Representative is Informed of the release timeline so they can prepare the FAQ update.

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Role-Based Checklists](checklists/role-based-checklists.md)
