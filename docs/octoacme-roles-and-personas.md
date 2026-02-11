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

## Scrum Master

### Role Summary
Scrum Masters enable agile delivery by facilitating ceremonies, coaching teams on agile practices, and removing process blockers. They ensure the team adheres to agile principles while maintaining focus on sprint goals.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Guide the team on agile best practices and self-organization
- Remove impediments and blockers that hinder team progress
- Shield the team from external distractions and context-switching
- Coach team members on continuous improvement
- Track sprint metrics and team velocity

### Goals
- Maximize team productivity and delivery flow
- Foster a culture of collaboration and transparency
- Ensure sprint commitments are achievable and met
- Continuously improve team processes and practices

### Typical Communication/Interaction
- Daily standups with Developers and QA/Testing
- Sprint planning and retrospectives with entire delivery team
- Coordination with Project Manager on risks and dependencies
- Regular sync with Product Manager on backlog readiness
- Escalation pathway to remove organizational impediments

---

## UX Designer

### Role Summary
UX Designers ensure products meet user needs and usability standards through research, prototyping, and iterative design. They bridge user requirements with technical implementation.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Collaborate on defining acceptance criteria with user experience focus
- Validate designs with stakeholders and end users
- Maintain design systems and component libraries
- Ensure accessibility standards are met

### Goals
- Deliver intuitive, user-friendly product experiences
- Validate design decisions with data and user feedback
- Reduce friction in user workflows
- Maintain consistency across product features

### Typical Communication/Interaction
- Early collaboration with Product Manager on requirements and user stories
- Design reviews with Developers to ensure feasibility
- Usability testing coordination with QA/Testing
- Feedback sessions with stakeholders and customers
- Handoff documentation and specifications to development team

---

## Technical Writer

### Role Summary
Technical Writers create and maintain documentation that enables users and internal teams to effectively use and understand products. They translate complex technical concepts into clear, accessible content.

### Responsibilities
- Create and update user manuals, API documentation, and guides
- Write release notes and change logs for each deployment
- Develop onboarding materials for new team members
- Maintain internal process documentation and runbooks
- Collaborate on UI copy and in-app help text
- Ensure documentation stays current with product changes

### Goals
- Provide accurate, up-to-date documentation for all audiences
- Reduce support burden through self-service resources
- Improve onboarding time for new users and team members
- Maintain consistent voice and style across all documentation

### Typical Communication/Interaction
- Works with Product Manager to understand feature intent and user needs
- Collaborates with Developers on technical accuracy and implementation details
- Coordinates with Project Manager on documentation timelines and deliverables
- Partners with DevOps Engineer on deployment and runbook documentation
- Reviews acceptance criteria to plan documentation needs

---

## DevOps Engineer

### Role Summary
DevOps Engineers ensure smooth build, deployment, and monitoring pipelines. They manage infrastructure, automate processes, and maintain system reliability and performance.

### Responsibilities
- Design and maintain CI/CD pipelines for automated testing and deployment
- Manage cloud infrastructure and provisioning
- Implement monitoring, alerting, and observability solutions
- Lead incident response and root cause analysis
- Automate operational tasks and improve deployment reliability
- Ensure security best practices in infrastructure and deployment

### Goals
- Achieve fast, reliable deployments with minimal downtime
- Maintain high system availability and performance
- Reduce manual operational overhead through automation
- Improve mean time to detection and recovery for incidents

### Typical Communication/Interaction
- Collaborates with Developers on build and deployment processes
- Works with QA/Testing during release validation and smoke tests
- Coordinates with Project Manager on release schedules and deployment windows
- Partners with Technical Writer on runbooks and operational documentation
- Escalates infrastructure risks and incidents to stakeholders

---

## Role Interactions and Project Lifecycle

### Initiation Phase
- **Product Manager** defines problem and success metrics
- **Project Manager** creates project charter and assembles team
- **UX Designer** conducts initial user research
- **Technical Writer** reviews documentation needs

### Planning Phase
- **Product Manager** prioritizes backlog with input from **UX Designer**
- **Scrum Master** facilitates sprint planning with **Developers** and **QA/Testing**
- **DevOps Engineer** identifies infrastructure and deployment requirements
- **Project Manager** maps dependencies and creates timeline
- **Technical Writer** plans documentation deliverables

### Execution Phase
- **Scrum Master** runs daily standups and removes blockers
- **Developers** implement features with **UX Designer** providing design specs
- **QA/Testing** validates quality with **DevOps Engineer** ensuring test environments
- **Technical Writer** drafts documentation in parallel with development
- **Project Manager** tracks progress and manages risks

### Release Phase
- **DevOps Engineer** executes deployment through CI/CD pipeline
- **QA/Testing** performs final validation and smoke tests
- **Technical Writer** finalizes release notes and user documentation
- **Product Manager** coordinates stakeholder communications
- **Project Manager** ensures release checklist completion

### Retrospective Phase
- **Scrum Master** facilitates retrospective and captures action items
- All roles provide feedback on process improvements
- **Project Manager** documents lessons learned and updates processes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The Role Interactions section clarifies handoffs and collaboration points across the project lifecycle.

