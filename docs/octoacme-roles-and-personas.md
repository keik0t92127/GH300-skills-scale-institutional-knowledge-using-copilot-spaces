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

## UX Researcher

### Role Summary
UX Researchers investigate user needs, behaviors, and pain points to ensure that product decisions are grounded in real customer insight. They partner with Product Managers and Developers to translate research findings into actionable requirements and usability improvements.

### Responsibilities
- Plan and conduct user interviews, surveys, and usability tests
- Synthesize qualitative and quantitative research into actionable insights
- Create and test prototypes to validate design assumptions early
- Maintain a user-research repository of findings and patterns
- Advocate for user needs throughout the product lifecycle

### Goals
- Reduce the gap between user expectations and delivered features
- Increase usability and customer satisfaction scores
- Enable evidence-based prioritization decisions
- Accelerate design iteration by surfacing issues early

### Typical Communication
- Research readouts shared with PdM and development leads after each study
- Participation in sprint planning to surface relevant user insights
- Usability-test plans reviewed with QA and Developers before execution

### Collaboration with Other Roles
| Interaction | With Whom | How |
|---|---|---|
| Requirements input | Product Manager | Provide research findings to inform feature scope and acceptance criteria |
| Design validation | Developers | Collaborate on prototypes and review UX implications of technical decisions |
| Test strategy | QA | Align usability test scenarios with functional test plans |
| Stakeholder alignment | Project Manager | Present research summaries at milestone reviews |
| Risk identification | Security Specialist | Flag privacy/consent requirements surfaced during user research |

---

## Security Specialist

### Role Summary
Security Specialists embed security practices into every phase of the project lifecycle. They perform risk assessments, lead threat-modeling sessions, review architectural decisions, and verify that releases meet security standards before reaching production.

### Responsibilities
- Define and communicate security requirements during initiation and planning
- Conduct threat modeling and risk assessments for new features and integrations
- Review designs, code, and infrastructure configurations for security vulnerabilities
- Validate security scans and penetration-test results before release
- Provide security training and guidance to the broader team
- Maintain and update the security incident runbook

### Goals
- Eliminate high-severity vulnerabilities before they reach production
- Shorten the time from vulnerability discovery to remediation
- Build a security-first culture across all roles
- Ensure compliance with relevant regulations and internal policies

### Typical Communication
- Threat-model workshops during planning phase
- Security-review sign-off included in the release checklist
- Incident notifications and post-mortems when security events occur

### Collaboration with Other Roles
| Interaction | With Whom | How |
|---|---|---|
| Requirements review | Product Manager | Ensure security requirements are captured in acceptance criteria |
| Architectural review | Developers | Review designs for attack surface and advise on secure-coding patterns |
| Release gate | Project Manager | Provide mandatory sign-off before production deployments |
| Risk register | Project Manager | Own security-related risk items and update mitigation status |
| UX consent & privacy | UX Researcher | Align on data-collection practices and user-consent flows |
| Compliance reporting | Stakeholders | Deliver security status summaries at major milestones |

---

## Data Analyst

### Role Summary
Data Analysts design measurement frameworks, collect and analyze data, and translate metrics into actionable insights. They work closely with Product Managers and Project Managers to ensure that key performance indicators (KPIs) are well-defined, tracked, and used in decision-making.

### Responsibilities
- Define KPIs and measurement plans aligned to project success criteria
- Design data-collection schemas and instrument tracking events
- Build and maintain dashboards to monitor product and operational metrics
- Analyze results of feature launches and experiments
- Identify data-quality issues and drive resolution
- Deliver regular metric readouts and ad-hoc analyses on request

### Goals
- Provide timely, accurate data to support evidence-based decisions
- Reduce reliance on intuition or anecdotal evidence in prioritization
- Improve data literacy across the team
- Enable rapid iteration by shortening the feedback loop between release and insight

### Typical Communication
- KPI design sessions with Product Manager during planning
- Dashboard reviews at sprint demos and weekly syncs
- Post-launch analysis reports shared with stakeholders

### Collaboration with Other Roles
| Interaction | With Whom | How |
|---|---|---|
| KPI definition | Product Manager | Co-create success metrics during initiation and planning |
| Instrumentation | Developers | Specify tracking events and review implementation |
| Experiment design | Product Manager / UX Researcher | Define hypotheses, sample sizes, and analysis plans |
| Risk & impact data | Project Manager | Supply data to support risk assessments and milestone decisions |
| Compliance & privacy | Security Specialist | Ensure data collection and retention complies with privacy policies |

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on continuous-improvement practices. They act as a servant-leader, protecting the team's focus and helping to optimize delivery processes.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and actively remove blockers and impediments
- Track and communicate sprint velocity, capacity, and burndown
- Coach the team on agile/scrum values and practices
- Shield the team from unplanned interruptions and scope creep
- Collaborate with Project Manager on cross-team dependencies and escalations

### Goals
- Maximize team throughput and predictability
- Foster a culture of transparency, inspection, and adaptation
- Reduce waste and unplanned work
- Enable sustainable pace and continuous improvement

### Typical Communication
- Daily facilitator of standups (timeboxed to 15 min)
- Sprint retrospective reports and action items shared with the team
- Impediment escalations communicated to Project Manager in writing

### Collaboration with Other Roles
| Interaction | With Whom | How |
|---|---|---|
| Sprint planning & backlog | Product Manager / Project Manager | Align on priorities, capacity, and Definition of Done each sprint |
| Impediment removal | Developers | Surface and resolve day-to-day blockers quickly |
| Process improvement | Project Manager | Coordinate process changes that affect cross-team workflows |
| Velocity reporting | Project Manager / Stakeholders | Provide sprint metrics to support project status reporting |
| Team health | All roles | Facilitate retrospectives and act on improvement actions |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Engagement Checklist](templates/role-engagement-checklist.md) for guidance on when to involve each role across project phases.

