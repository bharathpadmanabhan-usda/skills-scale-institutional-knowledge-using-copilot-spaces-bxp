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

## UX/UI Designer

### Role Summary
UX/UI Designers craft user-centered experiences by conducting research, designing interaction flows, and delivering prototypes that guide engineering implementation. They act as the voice of the user throughout the product lifecycle.

### Responsibilities
- Conduct user research (interviews, surveys, usability tests) and synthesize findings
- Create wireframes, interaction flows, and high-fidelity prototypes
- Maintain and evolve the design system and component library
- Present design proposals and gather feedback from Product Managers and Developers
- Validate implemented features against design specifications through design QA
- Ensure accessibility standards (WCAG) are met in all design deliverables

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce rework by validating designs early with engineering and stakeholders
- Champion the end-user perspective in all product decisions

### Typical Communication
- Design reviews with Product Managers and Developers during planning and execution
- Handoff of annotated design specs (e.g., Figma) to engineering at sprint start
- Usability test summaries shared with Product Managers post-sprint or post-release
- Async feedback via design tools and PR reviews on front-end implementation

### Collaboration with Existing Roles
- **Product Managers**: Co-define feature requirements and prioritize UX improvements based on research insights
- **Developers**: Clarify design intent, review front-end implementations, and agree on feasibility trade-offs
- **Project Managers**: Coordinate design milestones and ensure design readiness gates are met before engineering begins
- **QA/Testing**: Share design specs so testers can validate UI against intended experience

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They gather, document, and refine requirements to ensure the team builds the right thing for the right reasons.

### Responsibilities
- Elicit and document business requirements through workshops, interviews, and document analysis
- Translate business needs into functional and non-functional requirements
- Maintain a requirements traceability matrix linking business goals to backlog items
- Facilitate requirement review sessions with stakeholders and engineering
- Identify process gaps, inefficiencies, and opportunities for improvement
- Support acceptance testing by validating delivered solutions against requirements

### Goals
- Ensure delivered solutions meet stakeholder expectations and business objectives
- Reduce ambiguity and rework caused by incomplete or misunderstood requirements
- Improve alignment between business and technical teams

### Typical Communication
- Requirements workshops and stakeholder interviews during initiation and planning
- Written requirement documents, user stories, and acceptance criteria shared with Product Managers and Developers
- Change request documentation when scope changes arise
- Regular check-ins with Project Managers on requirement status and open questions

### Collaboration with Existing Roles
- **Product Managers**: Partner to refine the product backlog and ensure user stories reflect business value
- **Project Managers**: Flag scope changes promptly and maintain up-to-date requirement artifacts
- **Developers**: Answer technical questions about requirements and validate understanding during sprint planning
- **QA/Testing**: Provide acceptance criteria and support UAT (User Acceptance Testing) planning

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the toolchain, pipelines, and infrastructure that enable fast, reliable, and repeatable software delivery. They reduce friction between development and operations by automating build, test, and deployment workflows.

### Responsibilities
- Design, build, and maintain CI/CD pipelines (build, test, security scanning, deployment)
- Manage cloud or on-prem infrastructure using infrastructure-as-code (IaC) practices
- Monitor system health, configure alerting, and respond to infrastructure-level incidents
- Automate deployment and rollback procedures to minimize manual intervention
- Enforce security and compliance standards in the delivery pipeline
- Collaborate with Developers to improve build performance and reduce pipeline failures

### Goals
- Achieve fast, reliable, and fully automated deployments with minimal downtime
- Ensure infrastructure is reproducible, auditable, and cost-effective
- Reduce mean time to recovery (MTTR) for infrastructure-related incidents

### Typical Communication
- Release readiness reviews with Project Managers, Developers, and QA
- Infrastructure change notifications and deployment runbooks shared before release windows
- Post-incident reports reviewed in retrospectives
- Pipeline status dashboards accessible to the full team

### Collaboration with Existing Roles
- **Project Managers**: Coordinate deployment windows, communicate infrastructure risks, and confirm release readiness
- **Developers**: Review infrastructure requirements early in planning, pair on pipeline improvements and environment configuration
- **QA/Testing & QA Automation Engineers**: Ensure test environments mirror production and automated tests integrate seamlessly into pipelines
- **Support/Operations (SRE)**: Partner on monitoring strategy, on-call processes, and incident response runbooks

---

## QA Automation Engineer

### Role Summary
QA Automation Engineers build and maintain automated test suites that enable rapid, repeatable quality validation across the product. They ensure defects are caught early through CI-integrated testing while complementing manual QA efforts.

### Responsibilities
- Design, develop, and maintain automated test frameworks (unit, integration, end-to-end, regression)
- Integrate automated tests into CI/CD pipelines to enforce quality gates
- Collaborate with Developers to improve code testability and test coverage
- Triage and resolve flaky or failing automated tests
- Define and track test metrics (coverage, pass rates, flakiness) and report to the team
- Support shift-left testing by embedding quality checks early in the development cycle

### Goals
- Maximize automated test coverage while minimizing false positives and maintenance burden
- Reduce cycle time from commit to verified, deployable build
- Enable Developers to self-serve quality feedback without waiting for manual QA

### Typical Communication
- Test coverage and quality reports shared after each sprint
- Collaboration with Developers during sprint to instrument new features for testability
- Automated test results visible to the full team via CI dashboards
- Joint review of new test scenarios with QA/Testing for comprehensive coverage

### Collaboration with Existing Roles
- **Developers**: Pair on writing unit and integration tests, review test strategies for new features
- **QA/Testing**: Coordinate scope of automation vs. manual testing; share regression suites for validation
- **DevOps Engineers**: Align on CI pipeline configuration, test parallelization, and environment provisioning
- **Project Managers**: Report on test coverage trends and highlight quality risks that may affect release timelines

---

## Support/Operations (SRE or IT Support)

### Role Summary
Support/Operations engineers — whether Site Reliability Engineers (SREs) or IT Support specialists — are responsible for the health and reliability of production systems. They serve as the first line of response during incidents and feed operational learnings back into the product and process lifecycle.

### Responsibilities
- Monitor production systems using dashboards, logs, and alerting tools
- Respond to and coordinate incident resolution, escalating to Developers when needed
- Author and maintain incident runbooks, post-mortems, and knowledge base articles
- Participate in release reviews to assess operational risk and readiness
- Implement reliability improvements (error budgets, SLOs, capacity planning)
- Channel incident and support insights into retrospectives and backlog items

### Goals
- Maintain agreed service level objectives (SLOs) and minimize customer-impacting incidents
- Reduce repetitive toil through automation and self-service tooling
- Ensure every incident produces actionable learnings that improve future reliability

### Typical Communication
- Incident notifications and status updates to Project Managers, Developers, and Stakeholders during active incidents
- Post-incident reports reviewed with the broader team in retrospectives
- Release readiness input shared with DevOps Engineers and Project Managers before production deployments
- Support ticket trends and recurring issues surfaced in weekly syncs or planning sessions

### Collaboration with Existing Roles
- **Project Managers**: Escalate active incidents, provide operational risk assessments before releases, and flag recurring patterns that need backlog attention
- **Developers**: Collaborate on incident triage and root cause analysis; share observability requirements and runbook feedback
- **DevOps Engineers**: Jointly own on-call processes, monitoring infrastructure, and deployment safety practices
- **QA/Testing**: Share production defect patterns to inform regression test priorities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

