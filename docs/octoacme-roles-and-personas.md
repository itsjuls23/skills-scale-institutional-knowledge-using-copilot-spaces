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

### Interactions with Other Roles
- **With QA/Testing Lead:** Collaborate on testability requirements, respond to defect reports, and participate in test planning
- **With Technical Architect/Tech Lead:** Follow architectural guidance, participate in design reviews, and implement approved technical approaches
- **With Product Managers:** Clarify acceptance criteria, provide estimates, and communicate implementation trade-offs
- **With Project Managers:** Report progress in standups, flag blockers, and provide effort estimates for planning
- **With Security/Compliance Officer:** Implement security requirements and incorporate secure coding practices

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

### Interactions with Other Roles
- **With Developers:** Define acceptance criteria, provide product rationale, and validate implementations
- **With QA/Testing Lead:** Establish acceptance criteria and success metrics, review quality reports
- **With Technical Architect/Tech Lead:** Discuss feasibility and technical trade-offs, align on solution approach
- **With Project Managers:** Align on prioritization, scope, and milestone targets
- **With UX/Design Lead:** Collaborate on user experience and feature definition

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

### Interactions with Other Roles
- **With All Team Members:** Facilitate standups, planning sessions, and retrospectives; track progress and escalate blockers
- **With Product Managers:** Align on roadmap, scope, and prioritization; coordinate release planning
- **With Technical Architect/Tech Lead:** Track technical risks and dependencies; monitor architecture implementation
- **With QA/Testing Lead:** Coordinate test timelines and quality gates; incorporate quality metrics into reporting
- **With Security/Compliance Officer:** Track security and compliance risks; coordinate regulatory requirements

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads design and execute testing strategies to ensure that features meet acceptance criteria and quality standards. They collaborate with developers and product managers to define testability requirements and validate solutions.

### Responsibilities
- Develop test plans and test cases aligned with acceptance criteria
- Execute manual and automated testing across test environments
- Report defects with clear reproduction steps and severity
- Participate in sprint planning to identify test risks and dependencies
- Own quality metrics and test coverage reporting
- Advise on testability during design and development phases

### Goals
- Deliver high-quality features with minimal defects reaching production
- Reduce time-to-resolution for quality issues
- Increase confidence in release readiness

### Typical Communication
- Sprint planning and daily standups
- Test summary reports and defect logs
- Quality metrics reviews during stakeholder updates

### Interactions with Other Roles
- **With Developers:** Provide test cases and defect reports, collaborate on testability requirements during design
- **With Product Managers:** Clarify acceptance criteria, validate feature completeness, report quality status
- **With Technical Architect/Tech Lead:** Understand technical design to inform test strategy and environment setup
- **With Project Managers:** Report quality metrics, identify testing blockers, participate in release readiness assessments
- **With UX/Design Lead:** Validate user experience and usability requirements during testing

---

## Technical Architect / Tech Lead

### Role Summary
Technical Architects and Tech Leads define the technical strategy and architecture for projects. They guide design decisions, manage technical risks, and ensure solutions are scalable, maintainable, and aligned with organizational standards.

### Responsibilities
- Design technical architecture and system components
- Guide developers on implementation approaches and best practices
- Review pull requests and provide technical feedback
- Identify technical risks and propose mitigations
- Support capacity and effort estimation during planning
- Champion code quality, testing, and documentation standards

### Goals
- Deliver technically sound, scalable, and maintainable solutions
- Minimize technical debt and rework
- Share knowledge and develop team technical capabilities

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback
- Technical risk escalations in weekly syncs
- Mentoring and pairing with developers

### Interactions with Other Roles
- **With Developers:** Provide architectural guidance, review implementations, mentor on best practices and design patterns
- **With Product Managers:** Discuss feasibility, propose technical approaches, advise on trade-offs and scalability implications
- **With QA/Testing Lead:** Communicate architecture to inform test strategy and environment requirements
- **With Project Managers:** Escalate technical risks and dependencies, support effort estimation and capacity planning
- **With Security/Compliance Officer:** Incorporate security and compliance requirements into architecture design

---

## UX/Design Lead

### Role Summary
UX/Design Leads define and advocate for user-centered design solutions. They ensure features are intuitive, accessible, and aligned with user needs and organizational design systems.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Establish and maintain design systems and component libraries
- Collaborate with product and engineering on design feasibility
- Ensure accessibility and inclusive design practices
- Review implementations for design fidelity and user experience

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Establish consistent design language and component reuse
- Reduce support costs through improved usability

### Typical Communication
- Design reviews and critique sessions
- Wireframes, prototypes, and design specifications
- Usability test results and insights
- Design system documentation and guidelines

### Interactions with Other Roles
- **With Product Managers:** Collaborate on feature definition, validate user needs, and prioritize user-centered improvements
- **With Developers:** Provide detailed design specifications, review implementations for design fidelity, and support design system adoption
- **With QA/Testing Lead:** Validate user experience during testing, provide feedback on usability issues
- **With Project Managers:** Communicate design timelines and dependencies, participate in release planning
- **With Technical Architect/Tech Lead:** Discuss technical feasibility of design approaches and accessibility requirements

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects adhere to security best practices, compliance requirements, and organizational policies. They work with teams to identify and mitigate security risks.

### Responsibilities
- Conduct security reviews and threat assessments
- Define security requirements and acceptance criteria
- Review code and architecture for security vulnerabilities
- Ensure compliance with regulatory and organizational standards
- Provide guidance on secure coding and data handling practices
- Escalate critical security findings and recommend mitigations

### Goals
- Minimize security and compliance risks
- Embed security practices into the development lifecycle
- Maintain organizational reputation and regulatory compliance

### Typical Communication
- Security review meetings and threat assessments
- Compliance checklists and security signoff
- Incident escalation and response coordination
- Security training and guidance sessions

### Interactions with Other Roles
- **With Developers:** Provide secure coding guidance, review code for vulnerabilities, and support implementation of security requirements
- **With Technical Architect/Tech Lead:** Review architecture for security and compliance risks, advise on secure design patterns
- **With Product Managers:** Define security and compliance requirements, advise on regulatory implications of features
- **With Project Managers:** Escalate security and compliance risks, participate in risk management and release readiness
- **With QA/Testing Lead:** Coordinate security testing, define compliance validation criteria

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile processes and team workflows. They remove impediments, coach teams on agile practices, and help establish healthy team dynamics and continuous improvement.

### Responsibilities
- Facilitate sprint planning, standup, and retrospective meetings
- Help teams identify and resolve impediments
- Coach team members on agile principles and practices
- Protect team focus and minimize distractions
- Promote psychological safety and collaborative problem-solving
- Track team metrics and identify opportunities for process improvement

### Goals
- Enable teams to deliver value consistently and sustainably
- Foster continuous learning and process improvement
- Build high-performing, self-organizing teams

### Typical Communication
- Agile ceremonies (standups, planning, retrospectives)
- One-on-one coaching and feedback sessions
- Team health metrics and velocity tracking
- Process improvement action items

### Interactions with Other Roles
- **With Project Managers:** Coordinate on sprint planning, report on team capacity and blockers, support risk management discussions
- **With All Team Members:** Facilitate meetings, coach on agile practices, identify and help remove impediments
- **With Technical Architect/Tech Lead:** Support technical decision-making processes, facilitate design reviews when needed
- **With Product Managers:** Help clarify backlog items, support sprint planning prioritization

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interactions with Other Roles" sections to understand cross-functional dependencies and communication patterns.
