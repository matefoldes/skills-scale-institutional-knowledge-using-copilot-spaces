# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

**Related documents:**
- [Role Onboarding Checklist](octoacme-role-onboarding-checklist.md) — Template for onboarding new roles to a project
- [Role Responsibility Matrix](octoacme-role-responsibility-matrix.md) — RACI matrix for common activities

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

## QA / Quality Assurance

### Role Summary
QA Engineers validate that features meet acceptance criteria and quality standards. They design test strategies, execute manual and automated tests, and work with developers to prevent and identify defects early.

### Responsibilities
- Design and execute test plans and test cases
- Perform manual and automated testing
- Document and track bugs and issues
- Validate acceptance criteria and definition of done
- Collaborate with developers on testability and quality improvements

### Goals
- Ensure high product quality and minimal defects in production
- Shift testing left to catch issues early
- Improve test coverage and test automation

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Bug reports and test case documentation
- Daily standups and test status updates

### Interaction with Other Roles
- **Developers**: Collaborate on testability, reproduce and verify bug fixes
- **Product Managers**: Validate acceptance criteria and feature completeness
- **Project Managers**: Report testing status and risks
- **DevOps Engineer**: Coordinate test environment setup and CI/CD pipeline testing

### Example Ownership
- Test plans and test case documentation
- Bug reports and defect logs
- Test automation scripts
- QA sign-off for releases

### RACI Notes
- **Responsible** for test execution and quality validation
- **Accountable** for QA sign-off before release
- **Consulted** during feature design for testability

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, coach the team on agile practices, and remove impediments to help the team deliver value efficiently. They serve the team and organization by fostering continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Coach the team on agile principles and practices
- Identify and remove blockers and impediments
- Shield the team from external distractions
- Track team velocity and metrics
- Foster a culture of continuous improvement

### Goals
- Maximize team productivity and flow
- Promote self-organization and team ownership
- Enable predictable, sustainable delivery cadence
- Drive continuous improvement through retrospectives

### Typical Communication
- Facilitating all agile ceremonies
- One-on-ones with team members to identify blockers
- Metrics dashboards and burndown charts
- Retrospective action items

### Interaction with Other Roles
- **Developers**: Remove blockers, facilitate collaboration, coach on agile practices
- **Product Managers**: Collaborate on backlog refinement and sprint planning
- **Project Managers**: Coordinate on cross-team dependencies and project status
- **QA**: Ensure testing is integrated into sprint workflow

### Example Ownership
- Sprint ceremony facilitation
- Team velocity and metrics tracking
- Impediment log and resolution
- Retrospective action items

### RACI Notes
- **Responsible** for facilitating agile ceremonies and removing impediments
- **Accountable** for team process health and continuous improvement
- **Consulted** on process changes and team dynamics

---

## UX Designer

### Role Summary
UX Designers create user-centered designs that balance usability, accessibility, and business goals. They conduct user research, create wireframes and prototypes, and collaborate with product and engineering to deliver intuitive experiences.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user flows and information architecture
- Maintain design systems and style guides
- Validate designs through user feedback and metrics
- Ensure accessibility standards are met

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support flows
- Increase user satisfaction and engagement
- Maintain design consistency across products

### Typical Communication
- Design reviews and critique sessions
- User research findings and personas
- Wireframes, mockups, and prototype walkthroughs
- Accessibility audit reports

### Interaction with Other Roles
- **Developers**: Collaborate on implementation feasibility and design handoff
- **Product Managers**: Align on user needs, priorities, and success metrics
- **QA**: Coordinate on usability testing and acceptance criteria
- **Technical Writer**: Ensure consistency between UI and documentation

### Example Ownership
- Wireframes, mockups, and prototypes
- Design system and component library
- User research reports and personas
- Accessibility compliance documentation

### RACI Notes
- **Responsible** for design quality and user experience
- **Accountable** for UX design decisions and design system governance
- **Consulted** during feature planning and user research

---

## Technical Writer

### Role Summary
Technical Writers create clear, accurate documentation that helps users, developers, and stakeholders understand and use products effectively. They work with SMEs to document features, APIs, processes, and best practices.

### Responsibilities
- Write and maintain user guides, API documentation, and process docs
- Collaborate with developers and product teams on documentation requirements
- Ensure documentation accuracy and clarity
- Maintain documentation standards and style guides
- Create diagrams, screenshots, and video tutorials as needed
- Manage documentation versioning and releases

### Goals
- Provide clear, accessible documentation for all audiences
- Reduce support burden through self-service documentation
- Keep documentation up-to-date with product changes
- Improve documentation discoverability and usability

### Typical Communication
- Documentation reviews with SMEs
- Release notes and changelog updates
- Documentation feedback and improvement suggestions
- Style guide and standards discussions

### Interaction with Other Roles
- **Developers**: Gather technical details, review API and code documentation
- **Product Managers**: Align on feature documentation and user-facing content
- **UX Designer**: Ensure consistency between UI and documentation
- **Customer Success Manager**: Incorporate customer feedback into documentation

### Example Ownership
- User guides and tutorials
- API reference documentation
- Release notes and changelogs
- Internal process documentation

### RACI Notes
- **Responsible** for documentation creation and maintenance
- **Accountable** for documentation quality and accuracy
- **Informed** of all feature releases and product changes

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain infrastructure, CI/CD pipelines, and deployment automation. They enable teams to deliver software reliably and efficiently while maintaining security, performance, and observability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code (IaC)
- Configure monitoring, logging, and alerting systems
- Automate deployment and rollback processes
- Ensure security best practices in infrastructure
- Manage environments (dev, staging, production)
- Respond to incidents and perform root cause analysis

### Goals
- Enable fast, reliable, and safe deployments
- Minimize downtime and mean time to recovery (MTTR)
- Improve system observability and incident response
- Automate repetitive operations tasks

### Typical Communication
- Infrastructure changes and maintenance windows
- Incident reports and postmortems
- Performance and reliability metrics
- Security advisories and compliance reports

### Interaction with Other Roles
- **Developers**: Collaborate on deployment automation and environment needs
- **QA**: Provide test environments and CI/CD integration for automated tests
- **Project Managers**: Communicate deployment schedules and risks
- **Data Analyst**: Provide access to logs and metrics for analysis

### Example Ownership
- CI/CD pipeline configurations
- Infrastructure as code (Terraform, CloudFormation, etc.)
- Monitoring and alerting configurations
- Deployment runbooks and incident playbooks

### RACI Notes
- **Responsible** for infrastructure reliability and deployment automation
- **Accountable** for production environment stability
- **Consulted** on architecture decisions and scalability planning

---

## Customer Success Manager

### Role Summary
Customer Success Managers ensure customers achieve their desired outcomes using the product. They build relationships, drive adoption, identify expansion opportunities, and serve as the voice of the customer to product and engineering teams.

### Responsibilities
- Onboard new customers and drive product adoption
- Build and maintain customer relationships
- Monitor customer health and engagement metrics
- Identify upsell and expansion opportunities
- Gather customer feedback and communicate to product teams
- Resolve escalations and advocate for customer needs

### Goals
- Maximize customer retention and satisfaction
- Drive product adoption and usage
- Identify expansion revenue opportunities
- Reduce churn and escalations

### Typical Communication
- Customer check-ins and business reviews
- Customer health scorecards and metrics
- Feedback summaries and feature requests
- Escalation reports and resolution plans

### Interaction with Other Roles
- **Product Managers**: Share customer feedback and advocate for feature requests
- **Developers**: Escalate bugs and coordinate on customer-specific issues
- **Technical Writer**: Provide feedback on documentation gaps
- **Data Analyst**: Request customer usage reports and metrics

### Example Ownership
- Customer onboarding plans and playbooks
- Customer health scorecards
- Feature request tracking and prioritization
- Customer success metrics and reporting

### RACI Notes
- **Responsible** for customer relationships and satisfaction
- **Accountable** for retention and expansion goals
- **Consulted** on product roadmap and feature prioritization

---

## Data Analyst

### Role Summary
Data Analysts transform raw data into actionable insights that inform product, business, and engineering decisions. They build dashboards, conduct analyses, and collaborate with stakeholders to measure impact and identify opportunities.

### Responsibilities
- Design and build dashboards and reports
- Conduct exploratory data analysis and A/B test analysis
- Define and track key product and business metrics
- Collaborate with stakeholders to answer data questions
- Ensure data quality and accuracy
- Document data models and metrics definitions

### Goals
- Provide timely, accurate insights to drive decisions
- Enable self-service analytics for stakeholders
- Improve data quality and accessibility
- Measure product impact and identify opportunities

### Typical Communication
- Metrics dashboards and reports
- Analysis summaries and recommendations
- A/B test results and experiment reviews
- Data definitions and documentation

### Interaction with Other Roles
- **Product Managers**: Define and track success metrics, analyze feature impact
- **Developers**: Collaborate on instrumentation and data pipeline design
- **DevOps Engineer**: Access logs and system metrics for analysis
- **Customer Success Manager**: Provide customer usage reports and insights

### Example Ownership
- Metrics dashboards and reports
- A/B test analysis and documentation
- Data dictionary and metrics definitions
- Data quality monitoring and alerts

### RACI Notes
- **Responsible** for data analysis and reporting
- **Accountable** for metrics accuracy and data quality
- **Consulted** on product decisions requiring data insights

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

