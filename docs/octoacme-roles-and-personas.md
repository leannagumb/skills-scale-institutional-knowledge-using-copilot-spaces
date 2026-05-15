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

## Quality Assurance/Testing Lead

### Role Summary
QA/Testing Leads own quality strategy, define testing standards, and ensure products meet acceptance criteria before release. They collaborate with developers and product managers to validate that features work as intended and meet user expectations.

### Responsibilities
- Define testing strategy and QA approach for each project
- Create and maintain test plans and automated test suites
- Triage bugs and manage QA workflow
- Ensure acceptance criteria are testable and met before sign-off
- Identify quality risks and propose mitigation strategies
- Conduct manual testing and user acceptance validation
- Own post-release smoke tests and monitoring

### Goals
- Achieve defined quality standards and reduce production defects
- Shift-left by catching issues early in development
- Build team confidence in release readiness
- Maintain fast feedback loops with developers

### Typical Communication
- Sprint planning and backlog refinement reviews
- Daily QA status in standups
- Test plan reviews with Product and Project Managers
- Bug triage meetings and defect reporting
- Release readiness sign-offs

### Key Interactions
- **Developers**: Provides feedback on test failures, suggests improvements, collaborates on testability
- **Product Manager**: Validates acceptance criteria are testable; clarifies feature intent
- **Project Manager**: Reports on QA blockers, provides release readiness assessment
- **Technical Lead**: Discusses test automation architecture and testing complexity

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical guidance, design systems, and mitigate technical risks. They work with developers to ensure solutions are scalable, maintainable, and aligned with platform standards.

### Responsibilities
- Define technical design and architecture for projects
- Conduct technical design reviews and code reviews
- Identify and propose solutions for technical risks and dependencies
- Mentor developers and support capability building
- Ensure alignment with platform standards and technical governance
- Propose technical improvements and refactoring priorities
- Collaborate on performance, scalability, and security considerations

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and operational risk
- Build team technical capability and knowledge sharing
- Enable fast, reliable deployments

### Typical Communication
- Technical design review meetings
- Code review comments and design documentation
- Architecture decision records (ADRs)
- Technical risk discussions in planning and standups
- Cross-team technical sync for dependencies

### Key Interactions
- **Developers**: Provides design guidance, reviews code, supports problem-solving
- **QA/Testing Lead**: Discusses test automation design and testability strategies
- **Project Manager**: Flags technical risks and dependency impacts on schedule
- **Product Manager**: Explores technical trade-offs impacting scope or timeline

---

## Stakeholder/Sponsor

### Role Summary
Sponsors represent business interests, approve scope and funding, and provide strategic direction. They ensure projects align with organizational priorities and remove blockers escalated from the delivery team.

### Responsibilities
- Approve project charter and success metrics
- Provide or secure project funding and resource allocation
- Remove organizational blockers and escalations
- Provide strategic guidance on priority and scope changes
- Approve major releases and go/no-go decisions
- Communicate project status to executive leadership
- Champion project outcomes and adoption

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy
- Minimize scope creep and timeline slippage
- Support team success through resource and political support

### Typical Communication
- Project initiation and approval meetings
- Monthly executive status updates
- Major milestone reviews and sign-offs
- Escalation resolution (ad-hoc)
- Release announcements and celebration

### Key Interactions
- **Project Manager**: Receives status updates and escalations; approves scope changes
- **Product Manager**: Aligns on priority and business metrics; approves roadmap trade-offs
- **Delivery Team**: Provides decision authority on blockers and strategic questions

---

## Design/UX Lead

### Role Summary
Design/UX Leads own the user experience strategy, design systems, and usability validation. They collaborate with product and development teams to ensure solutions are intuitive, accessible, and meet user needs.

### Responsibilities
- Define UX strategy and design standards for projects
- Create wireframes, prototypes, and design specifications
- Conduct user research and usability testing
- Maintain design systems and component libraries
- Review designs for accessibility and consistency
- Collaborate on feature scope to optimize user experience
- Support acceptance criteria definition for UI/UX features

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Maintain design consistency across products
- Support data-driven design decisions

### Typical Communication
- Product discovery and research sharing
- Design reviews and feedback sessions
- Sprint planning and backlog refinement
- User testing and feedback reports
- Accessibility and design system guidance

### Key Interactions
- **Product Manager**: Collaborates on feature definition and user research
- **Developers**: Provides design specs, reviews implementation; supports accessibility
- **QA/Testing Lead**: Defines UX acceptance criteria and usability test plans
- **Project Manager**: Discusses design complexity and schedule impact

---

## DevOps/Platform Engineer

### Role Summary
DevOps/Platform Engineers own infrastructure, deployment pipelines, and operational excellence. They enable the team to deploy reliably and monitor production systems.

### Responsibilities
- Design and maintain deployment pipelines (CI/CD)
- Manage infrastructure and cloud platforms
- Ensure system reliability and uptime
- Implement monitoring, logging, and alerting
- Support incident response and troubleshooting
- Manage secrets, access control, and security compliance
- Optimize performance and cost efficiency

### Goals
- Enable fast, reliable, safe deployments
- Maintain high system availability and performance
- Reduce mean-time-to-recovery (MTTR) for incidents
- Support operational excellence and cost efficiency

### Typical Communication
- Release readiness sign-offs
- Deployment coordination and runbooks
- Infrastructure requirements in planning
- Incident response and post-mortems
- Performance and reliability metrics reviews

### Key Interactions
- **Project Manager**: Coordinates deployment windows and rollout plans
- **Developers**: Supports pipeline issues; provides infrastructure guidance
- **Security Lead**: Collaborates on secrets management and compliance requirements
- **Technical Lead**: Discusses infrastructure architecture and scaling

---

## Security Lead

### Role Summary
Security Leads ensure projects meet security compliance standards, conduct threat modeling, and manage security incidents. They work across teams to embed security into the development lifecycle.

### Responsibilities
- Conduct threat modeling and security design reviews
- Define security requirements and acceptance criteria
- Manage security scanning and vulnerability remediation
- Support incident response for security issues
- Ensure compliance with security policies and standards
- Provide security training and guidance to teams
- Manage security escalations and disclosure

### Goals
- Prevent security vulnerabilities and data breaches
- Ensure compliance with organizational and regulatory standards
- Build team security awareness and practices
- Enable secure-by-design development

### Typical Communication
- Security design reviews and threat modeling sessions
- Security requirements in backlog items
- Vulnerability scanning and remediation reports
- Security incident escalations and post-mortems
- Compliance and audit coordination

### Key Interactions
- **Project Manager**: Flags security risks and escalates incidents
- **Developers**: Provides security guidance and code review feedback
- **Technical Lead**: Collaborates on secure architecture design
- **DevOps/Platform Engineer**: Ensures secrets management and infrastructure security
- **QA/Testing Lead**: Defines security testing and acceptance criteria

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
