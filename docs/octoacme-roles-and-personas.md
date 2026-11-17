# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign these roles according to project size and expertise; one person may cover multiple roles, but each responsibility and decision owner should be explicit.

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
- Work with the Product Manager and Business Analyst to clarify requirements and acceptance criteria.
- Coordinate implementation details and technical decisions with the Technical Lead/Architect.
- Partner with the UX/UI Designer to implement accessible, usable designs, and with QA/Testing to diagnose defects and improve testability.
- Coordinate delivery dependencies, risks, and status with the Project Manager; consult the Security/Privacy Lead and DevOps/Release Engineer where their expertise is needed.

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
- Set desired outcomes and priorities with Stakeholders and the Project Manager, then work with the Business Analyst to make needs and scope clear.
- Collaborate with the UX/UI Designer on user needs and experience trade-offs, and with Developers and the Technical Lead/Architect on feasibility and technical options.
- Ensure security and privacy needs are considered with the Security/Privacy Lead; coordinate release readiness and communications with the DevOps/Release Engineer and Project Manager.

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
- Coordinate plans, milestones, resources, dependencies, and escalations across all roles; maintain the shared status and risk information.
- Align scope and priority with the Product Manager, and delivery estimates and technical dependencies with the Technical Lead/Architect and Developers.
- Schedule requirements, design, security, QA, and release reviews with the relevant specialists; communicate decisions and blockers to Stakeholders.

---

## UX/UI Designers

### Role Summary
UX/UI Designers research user needs and shape accessible, understandable, and usable product experiences through workflows, interaction patterns, and visual design.

### Responsibilities
- Explore user journeys and translate research and product goals into designs
- Create and maintain wireframes, prototypes, interaction specifications, and design guidance
- Consider accessibility and usability throughout design
- Gather feedback and refine designs based on testing and stakeholder input
- Identify design assumptions, dependencies, and open questions

### Goals
- Deliver coherent, accessible experiences that meet user needs
- Reduce ambiguity before implementation and prevent avoidable usability issues

### Typical Communication
- Design reviews, prototypes, and research findings
- Collaboration with product and delivery teams during planning and implementation
- Usability and accessibility findings shared with QA/Testing and Stakeholders

### Interactions
- Partner with the Product Manager and Stakeholders to understand user needs and product outcomes, and with the Business Analyst to connect workflows to business requirements.
- Coordinate feasibility and implementation details with Developers and the Technical Lead/Architect.
- Work with QA/Testing to define usability and accessibility checks; coordinate design review timing and dependencies with the Project Manager.

---

## Business Analysts

### Role Summary
Business Analysts clarify business needs and processes, translate them into well-defined requirements, and maintain traceability from needs to delivered outcomes.

### Responsibilities
- Elicit and document business requirements, workflows, assumptions, and constraints
- Break down requirements into clear, testable acceptance criteria with the Product Manager
- Identify gaps, dependencies, and impacts of proposed changes
- Maintain traceability between stakeholder needs, backlog items, and validation
- Facilitate requirement reviews and resolve ambiguity

### Goals
- Ensure the team shares an accurate understanding of the problem and scope
- Make requirements testable and aligned with intended outcomes

### Typical Communication
- Requirements and process documentation
- Workshops and clarification sessions with Stakeholders and delivery roles
- Backlog refinement and acceptance-criteria reviews

### Interactions
- Work with the Product Manager to align requirements with product goals and priorities, and with Stakeholders to elicit and validate business needs.
- Clarify requirements for Developers and the Technical Lead/Architect; collaborate with QA/Testing to make acceptance criteria verifiable.
- Coordinate analysis milestones and dependencies with the Project Manager, and consult the UX/UI Designer and Security/Privacy Lead when user experience or data protection requirements affect scope.

---

## Technical Leads / Architects

### Role Summary
Technical Leads/Architects guide technical design and integration decisions, support engineering quality, and help identify and manage technical risks.

### Responsibilities
- Define or review architecture, interfaces, and integration approaches
- Identify technical constraints, dependencies, and risks and propose mitigations
- Support estimates and break down technically complex work
- Promote maintainability, reliability, and appropriate engineering practices
- Advise on technical trade-offs and help keep implementation aligned with the agreed design

### Goals
- Enable a secure, reliable, maintainable solution that meets product needs
- Surface technical decisions and risks early enough for the team to act

### Typical Communication
- Design proposals and architecture decision records
- Technical reviews and implementation guidance
- Estimates, dependency updates, and risk discussions

### Interactions
- Collaborate with the Product Manager on feasibility and trade-offs, and with the Project Manager on estimates, dependencies, and technical risks.
- Guide Developers through design and implementation while preserving their ownership of assigned work.
- Work with QA/Testing on testability and integration strategy, the DevOps/Release Engineer on operational needs, and the Security/Privacy Lead on security architecture and controls.

---

## DevOps / Release Engineers

### Role Summary
DevOps/Release Engineers help teams build, deploy, and operate software reliably through delivery automation, environment management, and release support.

### Responsibilities
- Maintain or advise on CI/CD pipelines and deployment automation
- Coordinate application environments and deployment prerequisites
- Support release readiness, monitoring, and rollback or mitigation planning
- Improve operational observability and communicate deployment risks
- Help ensure release procedures are repeatable and documented

### Goals
- Enable safe, predictable releases and reliable operations
- Reduce manual deployment risk and improve visibility into service health

### Typical Communication
- Pipeline and environment documentation
- Release checklists, deployment plans, and operational dashboards
- Readiness and post-deployment updates with delivery and stakeholder teams

### Interactions
- Coordinate pipeline, environment, and operational needs with Developers, the Technical Lead/Architect, and QA/Testing.
- Align release windows, dependencies, and risks with the Project Manager; support the Product Manager with readiness information and stakeholder release communications.
- Consult the Security/Privacy Lead on deployment controls and sensitive data handling, and share monitoring and incident signals with the team after release.

---

## Security / Privacy Leads

### Role Summary
Security/Privacy Leads advise teams on security and privacy requirements, risk assessment, and appropriate review or approval checkpoints for the product and its data.

### Responsibilities
- Identify applicable security and privacy requirements and review points
- Facilitate threat, privacy, and risk assessments appropriate to the work
- Recommend controls and help teams track security or privacy risks and mitigations
- Review validation evidence and raise material concerns through established escalation paths
- Help ensure security and privacy considerations are addressed throughout delivery, not only before release

### Goals
- Reduce security and privacy risks and support responsible handling of data
- Make requirements, controls, and unresolved risks visible to decision-makers

### Typical Communication
- Security and privacy requirements, reviews, and risk assessments
- Findings and mitigation tracking with engineering and QA/Testing
- Escalations through the documented risk and incident communication paths

### Interactions
- Work with the Product Manager and Stakeholders to understand data use, obligations, and acceptable risk; advise the Business Analyst on capturing these as requirements.
- Partner with Developers and the Technical Lead/Architect on controls and design choices, and with QA/Testing on security validation.
- Coordinate review checkpoints and risk status with the Project Manager; advise the DevOps/Release Engineer on deployment and operational controls. Escalate security incidents through the established security incident process.

---

## QA / Testing

### Role Summary
QA/Testing validates that delivered work meets acceptance criteria and quality expectations through appropriate test planning and execution.

### Responsibilities
- Collaborate on testability and validation plans during planning and implementation
- Create and maintain relevant automated and manual tests
- Validate acceptance criteria, integrations, and critical user flows
- Report defects clearly and help the team verify fixes
- Contribute quality signals and residual risks to release readiness discussions

### Goals
- Detect important issues early and provide trustworthy evidence of product quality
- Support releases that meet agreed acceptance and quality standards

### Typical Communication
- Test plans, test results, and defect reports
- CI results and release-readiness updates
- Coordination with Developers, Designers, and product and project leads

### Interactions
- Work with the Product Manager and Business Analyst to understand expected behavior and acceptance criteria.
- Coordinate with Developers and the Technical Lead/Architect on testability, fixes, and integration coverage; validate usability and accessibility with the UX/UI Designer.
- Coordinate environments and release checks with the DevOps/Release Engineer, and security testing with the Security/Privacy Lead.
- Share quality status, blockers, and residual risks with the Project Manager and Stakeholders through the agreed project cadence.

---

## Stakeholders

### Role Summary
Stakeholders represent groups affected by or invested in the project and provide context, feedback, and decisions within their areas of responsibility.

### Responsibilities
- Share needs, constraints, and relevant domain expertise
- Review proposals and deliverables at agreed checkpoints
- Provide timely decisions and feedback within their delegated authority
- Help assess outcomes and communicate impacts to their groups

### Goals
- Ensure project outcomes address relevant needs and constraints
- Make decisions with clear understanding of trade-offs and impacts

### Typical Communication
- Kickoffs, milestone reviews, and regular status updates
- Decision requests, demos, and release communications
- Feedback and outcome reviews

### Interactions
- Partner with the Product Manager and Business Analyst to clarify needs and validate scope and outcomes.
- Provide timely input to the UX/UI Designer and relevant specialists; rely on the Project Manager for coordinated updates, risks, and decision requests.
- Participate in reviews and decisions appropriate to their authority without replacing specialist recommendations or the named accountable decision owner.

---

## Role Boundaries and Collaboration Across the Lifecycle

- Initiation: The Product Manager frames the problem and success measures with Stakeholders. The Project Manager coordinates alignment; the Business Analyst and specialists surface requirements, constraints, and early risks.
- Planning: The Product Manager owns product priorities, while the Project Manager coordinates the delivery plan. The Business Analyst refines requirements; the UX/UI Designer, Technical Lead/Architect, Security/Privacy Lead, Developers, QA/Testing, and DevOps/Release Engineer contribute design, estimates, quality, risk, and release input.
- Execution: Developers implement the agreed work. Specialists provide guidance and validation in their areas; the Product Manager resolves product priority questions, and the Project Manager tracks progress, dependencies, decisions, and escalations.
- Release: QA/Testing reports acceptance and quality evidence. The DevOps/Release Engineer supports deployment and operational readiness; the Security/Privacy Lead advises on outstanding security or privacy risks. The Product Manager and Stakeholders align on product readiness and communications, while the Project Manager coordinates the release plan.
- Retrospective: The Project Manager facilitates the review; all roles contribute learnings and owned follow-up actions. The Product Manager connects improvements to outcomes and priorities.

These roles may be combined or tailored to project size, but each project should make ownership, decision authority, review responsibilities, and escalation paths explicit. Specialist advice informs decisions; approval authority remains with the person or governance process designated by the project.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
