# OctoAcme Role Responsibility Matrix

## Purpose
This RACI matrix clarifies who is Responsible, Accountable, Consulted, and Informed for common project activities. Use it to reduce confusion during handoffs, improve decision-making speed, and ensure clear accountability.

## RACI Definitions
- **R (Responsible):** Does the work to complete the task
- **A (Accountable):** Ultimately answerable for the task's completion and has approval authority (only one A per activity)
- **C (Consulted):** Provides input and expertise before decisions or actions are taken
- **I (Informed):** Kept up to date on progress and decisions

---

## Matrix: Common Project Activities

| Activity | PM | PdM | Dev | QA | Scrum Master | UX | Tech Writer | DevOps | CSM | Data Analyst |
|----------|----|----|-----|----|--------------|----|-------------|--------|-----|--------------|
| **Backlog Prioritization** | C | A | C | I | C | C | I | I | C | C |
| **Sprint Planning** | C | C | R | R | A | C | I | C | I | C |
| **Feature Design** | I | C | C | I | I | A/R | I | I | I | C |
| **Code Implementation** | I | I | A/R | C | I | C | I | C | I | I |
| **Code Review** | I | I | R/A | C | I | I | I | C | I | I |
| **Testing & QA** | I | C | C | A/R | I | I | I | C | I | I |
| **Release Sign-off** | R | A | C | C | I | C | C | C | I | I |
| **Deployment** | C | I | C | I | I | I | I | A/R | I | I |
| **Incident Response** | C | I | R | C | I | I | I | A | C | C |
| **Documentation (User Docs)** | I | C | C | I | I | C | A/R | I | C | I |
| **Documentation (Technical)** | I | I | R | I | I | I | C | R | I | I |
| **User Research** | C | A | I | I | I | R | I | I | C | C |
| **A/B Test Analysis** | I | A | I | I | I | I | I | I | C | R |
| **Metrics & Reporting** | C | A | I | I | I | I | I | C | C | R |
| **Retrospective** | C | C | R | R | A | R | R | R | R | R |
| **Risk Identification** | A | C | R | R | C | C | C | R | C | C |
| **Stakeholder Updates** | A/R | R | I | I | C | I | I | I | C | C |
| **Customer Escalations** | C | C | C | I | I | I | I | C | A/R | C |
| **Onboarding New Team Members** | R | C | C | C | R | C | C | C | I | C |

**Legend:**
- **PM**: Project Manager
- **PdM**: Product Manager
- **Dev**: Developer
- **QA**: Quality Assurance
- **Scrum Master**: Agile facilitator and coach
- **UX**: UX Designer
- **Tech Writer**: Technical Writer
- **DevOps**: DevOps Engineer
- **CSM**: Customer Success Manager
- **Data Analyst**: Data/Analytics Specialist

---

## Activity Descriptions

### Backlog Prioritization
Deciding what features and work items should be prioritized in the upcoming sprints.
- **PdM** decides based on customer value, business goals, and stakeholder input.
- **PM**, **Dev**, **Scrum Master**, **UX**, **CSM**, **Data Analyst** provide input on feasibility, risks, and customer needs.

### Sprint Planning
Selecting and committing to work for the upcoming sprint.
- **Scrum Master** facilitates the ceremony and ensures process is followed.
- **Dev** and **QA** estimate and commit to work.
- **PM**, **PdM**, **UX**, **DevOps**, **Data Analyst** consulted for context and dependencies.

### Feature Design
Creating user flows, wireframes, and interaction designs.
- **UX** owns design decisions and deliverables.
- **PdM** provides product context and validates alignment with user needs.
- **Dev** consulted on technical feasibility.

### Code Implementation
Writing and delivering code for features and fixes.
- **Dev** owns implementation and is accountable for quality.
- **QA**, **UX**, **DevOps** consulted during implementation.

### Code Review
Reviewing and approving code changes.
- **Dev** reviews peer code and ensures standards are met.
- **QA**, **DevOps** may be consulted for test coverage and deployment concerns.

### Testing & QA
Validating that features meet acceptance criteria and quality standards.
- **QA** owns test execution and sign-off.
- **PdM** consulted to validate acceptance criteria.
- **Dev** collaborates on bug fixes.

### Release Sign-off
Approving a release to go to production.
- **PdM** accountable for final go/no-go decision.
- **PM** coordinates sign-off process.
- **Dev**, **QA**, **UX**, **DevOps** consulted on readiness.

### Deployment
Executing the release to production.
- **DevOps** accountable for deployment process and rollback readiness.
- **PM**, **Dev** consulted on timing and coordination.

### Incident Response
Responding to production incidents and restoring service.
- **DevOps** accountable for incident management and resolution.
- **Dev** responsible for diagnosing and fixing issues.
- **PM**, **QA**, **CSM**, **Data Analyst** consulted or informed as needed.

### Documentation (User Docs)
Creating and maintaining user-facing documentation (guides, FAQs, tutorials).
- **Tech Writer** accountable for documentation quality and completeness.
- **PdM**, **UX**, **CSM** consulted to ensure accuracy and usefulness.

### Documentation (Technical)
Creating technical documentation (architecture, API docs, runbooks).
- **Dev** and **DevOps** responsible for documenting technical details.
- **Tech Writer** may assist with formatting and clarity.

### User Research
Conducting research to understand user needs and validate designs.
- **UX** responsible for research execution.
- **PdM** accountable for ensuring research aligns with product strategy.
- **PM**, **CSM**, **Data Analyst** consulted for context.

### A/B Test Analysis
Analyzing experiment results to inform product decisions.
- **Data Analyst** responsible for analysis and insights.
- **PdM** accountable for acting on insights.
- **UX**, **Dev**, **CSM** consulted or informed.

### Metrics & Reporting
Tracking and reporting product and project metrics.
- **Data Analyst** responsible for building reports and dashboards.
- **PdM** accountable for defining metrics and interpreting results.
- **PM** consulted for project-level metrics.

### Retrospective
Reflecting on sprint/project performance and identifying improvements.
- **Scrum Master** accountable for facilitating the retrospective.
- All team members (Dev, QA, UX, Tech Writer, DevOps, CSM, Data Analyst) participate and contribute.

### Risk Identification
Identifying and documenting project risks.
- **PM** accountable for maintaining the risk register.
- **Dev**, **QA**, **DevOps** responsible for identifying technical risks.
- **PdM**, **Scrum Master**, **UX**, **Tech Writer**, **CSM**, **Data Analyst** consulted.

### Stakeholder Updates
Communicating project status, risks, and decisions to stakeholders.
- **PM** accountable for regular status updates.
- **PdM** responsible for product-level updates.
- **Scrum Master** consulted on team health and velocity.

### Customer Escalations
Managing and resolving urgent customer issues.
- **CSM** accountable for customer satisfaction and escalation resolution.
- **PM**, **PdM**, **Dev**, **DevOps**, **Data Analyst** consulted to resolve issues.

### Onboarding New Team Members
Integrating new team members into the project.
- **PM** and **Scrum Master** responsible for coordinating onboarding.
- **PdM**, **Dev**, **QA**, **UX**, **Tech Writer**, **DevOps** consulted to provide context and training.

---

## How to Use This Matrix

### For New Projects
1. Review and customize this matrix for your project's specific roles and activities
2. Discuss and align on RACI assignments during project kickoff
3. Document any customizations in your project charter
4. Reference this matrix when confusion arises about ownership

### For Role Transitions and Handoffs
1. Use this matrix to identify what responsibilities transfer
2. Schedule handoff sessions for activities where the role is R or A
3. Update project documentation if RACI assignments change
4. Communicate changes to all affected team members

### For Conflict Resolution
1. When ownership is unclear, reference this matrix
2. If the matrix doesn't cover the activity, discuss and document the decision
3. Update the matrix if the activity is recurring
4. Escalate to PM or PdM if agreement cannot be reached

---

## Customization Notes

This is a general-purpose matrix. Actual RACI assignments may vary based on:
- Team size and structure
- Project complexity and risk level
- Organizational standards and policies
- Tool and process maturity

**Recommended:** Review and update this matrix during project initiation and retrospectives to keep it relevant and accurate.

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role definitions
- [Role Onboarding Checklist](octoacme-role-onboarding-checklist.md) — Template for onboarding new roles
- [Project Management Overview](octoacme-project-management-overview.md) — High-level project approach
