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

## QA / Testing

### Role Summary
QA and Testing contributors validate that features meet acceptance criteria, are regression-free, and are ready for production. They are the last line of quality assurance before release.

### Responsibilities
- Write and execute test plans and test cases aligned to acceptance criteria
- Perform exploratory, regression, and end-to-end testing
- Raise, track, and verify bug fixes
- Validate release readiness in staging environments
- Maintain smoke test suites for critical flows

### Goals
- Prevent defects from reaching production
- Provide rapid, reliable feedback during development sprints
- Continuously improve test coverage and test infrastructure

### Typical Communication
- Daily standups and sprint reviews with the development team
- Bug reports and test result summaries
- Staging readiness sign-offs shared with PM and Developers

### Interaction with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Reports release readiness status; flags quality blockers that may affect timelines |
| Product Manager | Validates acceptance criteria interpretation; clarifies edge cases from user/business perspective |
| Developers | Reviews PRs for testability; receives bug reports; collaborates on test strategy for complex features |
| Stakeholders | Informs stakeholders of quality risks when appropriate through the PM |

---

## Stakeholders

### Role Summary
Stakeholders are internal or external parties with a vested interest in project outcomes. They provide business context, approve scope and priorities, and receive regular progress communications.

### Responsibilities
- Provide business requirements, constraints, and strategic context
- Approve project charters, milestones, and scope changes
- Review and action escalations when required
- Participate in demos and acceptance reviews

### Goals
- Ensure project outcomes align with business strategy
- Maintain confidence in delivery timelines and quality
- Minimize surprises through proactive communication

### Typical Communication
- Milestone and weekly status updates from PM
- Executive summaries and risk escalations
- Sprint demos and release notes

### Interaction with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Primary point of contact for status, risks, and escalations |
| Product Manager | Collaborates on prioritization and outcome validation |
| Developers | Indirect — may participate in demos and acceptance reviews |
| QA/Testing | Indirect — receives quality signals via PM communications |

---

## Technical Lead

### Role Summary
The Technical Lead owns technical direction, architecture decisions, and implementation quality standards. They bridge the gap between product requirements and engineering execution.

### Responsibilities
- Define and steward architectural decisions and technical standards
- Lead technical design reviews and establish code review expectations
- Identify and mitigate technical risks and dependencies
- Support estimation accuracy and sprint capacity planning
- Mentor and guide Developers through complex technical challenges

### Goals
- Ensure a scalable, maintainable, and secure codebase
- Reduce technical debt and unplanned rework
- Accelerate delivery through clear technical direction

### Typical Communication
- Technical design documents and architecture decision records (ADRs)
- Code review comments and engineering standards documentation
- Risk and dependency updates shared with PM during planning

### Interaction with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Provides dependency and technical risk visibility; assists with estimation and schedule trade-offs |
| Product Manager | Advises on technical feasibility and scope trade-offs during discovery and planning |
| Developers | Guides design, reviews code, and resolves blockers; sets quality and style standards |
| QA/Testing | Aligns on test strategy for complex or high-risk changes |
| Stakeholders | Participates in technical briefings and architecture reviews when relevant |

---

## Engineering Manager

### Role Summary
The Engineering Manager focuses on team health, capacity planning, and sustainable delivery. They ensure Developers have the environment and support they need to do their best work.

### Responsibilities
- Own team capacity planning, staffing, and career development
- Remove organizational and process blockers for the engineering team
- Align team workload with project commitments and roadmap priorities
- Support Developer performance, well-being, and professional growth
- Coordinate hiring, onboarding, and team structure decisions

### Goals
- Maintain a high-performing, sustainable engineering team
- Align delivery commitments with realistic team capacity
- Foster a culture of psychological safety and continuous improvement

### Typical Communication
- Capacity and staffing updates to Project Manager and Product Manager
- 1:1 and team-level performance and health discussions
- Resource constraint communications to stakeholders through PM

### Interaction with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Aligns roadmap commitments with team capacity; communicates staffing risks and constraints |
| Product Manager | Collaborates on roadmap sequencing based on team bandwidth and technical priorities |
| Developers | Provides performance support, removes blockers, and facilitates career growth |
| QA/Testing | Ensures QA resources are staffed and supported alongside development capacity |
| Stakeholders | Coordinates on resource constraints and delivery confidence through PM |

---

## UX / UI Designer

### Role Summary
The UX/UI Designer defines user flows, interaction design, accessibility standards, and visual specifications. They translate user needs into implementation-ready design artifacts.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Create wireframes, prototypes, and final UI specifications
- Define accessibility requirements and interaction patterns
- Ensure design consistency through shared design systems and style guides
- Participate in sprint planning and acceptance reviews to validate implementation fidelity

### Goals
- Deliver intuitive and accessible user experiences
- Reduce rework through clear, implementation-ready design handoffs
- Ensure feature usability meets or exceeds user expectations

### Typical Communication
- Design files and annotated specs shared with Developers before sprint start
- Usability findings and design rationale documentation
- Design review sessions and acceptance feedback during sprint reviews

### Interaction with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Communicates design dependencies and timelines; flags design blockers |
| Product Manager | Collaborates on discovery, user research, and prioritization of UX improvements |
| Developers | Provides implementation-ready design assets; reviews implemented UI for fidelity |
| QA/Testing | Aligns acceptance expectations for visual and interaction requirements |
| Stakeholders | Presents design concepts and usability findings in demos and reviews |

---

## DevOps / Platform Engineer

### Role Summary
The DevOps/Platform Engineer owns CI/CD reliability, deployment automation, environment management, observability, and release safety controls. They ensure the platform enables fast, reliable delivery.

### Responsibilities
- Design and maintain CI/CD pipelines and build automation
- Manage infrastructure, environments, and platform tooling
- Implement observability — logging, alerting, and monitoring
- Define and enforce release safety controls (feature flags, rollback procedures, canary deployments)
- Respond to platform incidents and minimize mean time to recovery (MTTR)

### Goals
- Enable safe, frequent, and automated deployments
- Maximize platform reliability and developer productivity
- Reduce deployment risk and incident impact

### Typical Communication
- Pipeline and environment status dashboards
- Incident reports and post-mortems
- Release readiness confirmations and runbooks shared with PM and QA

### Interaction with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Supports release planning and communicates platform risks; participates in risk register reviews |
| Product Manager | Advises on infrastructure cost, scalability, and platform constraints that affect roadmap decisions |
| Developers | Maintains pipelines and tooling used by Developers; collaborates on build and deploy improvements |
| QA/Testing | Ensures staging environments are production-like and reliable for QA; supports smoke test automation |
| Stakeholders | Provides platform reliability metrics and incident summaries through PM |

---

## Business Analyst (BA)

### Role Summary
The Business Analyst bridges business needs and technical execution by translating stakeholder requirements into clear specifications, process flows, and traceable acceptance criteria.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Create process flows, user stories, and use case documentation
- Define and verify acceptance criteria with Product Manager and Developers
- Maintain requirements traceability through the project lifecycle
- Support scope management by identifying gaps, ambiguities, and change impacts

### Goals
- Ensure requirements are clear, testable, and consistently understood across the team
- Reduce rework caused by ambiguous or missing specifications
- Enable faster decision-making by providing structured analysis and impact assessments

### Typical Communication
- Requirements documents and user story refinement sessions
- Acceptance criteria walkthroughs with Developers and QA
- Impact analysis reports for scope changes shared with PM and Product Manager

### Interaction with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Provides scope clarity and supports change impact analysis; helps maintain the requirements baseline |
| Product Manager | Collaborates to refine business needs into detailed requirements and acceptance criteria |
| Developers | Clarifies requirements and edge cases during development; validates interpretations before implementation |
| QA/Testing | Supports test case development by providing detailed requirements and expected behaviors |
| Stakeholders | Facilitates requirements workshops and validates that documented needs reflect business intent |

---

## Customer Success / Support Liaison

### Role Summary
The Customer Success/Support Liaison provides the team with customer-facing insights, recurring support patterns, and post-release feedback loops. They ensure the voice of the customer informs prioritization and release decisions.

### Responsibilities
- Collect and synthesize customer feedback, support tickets, and usage patterns
- Communicate high-impact customer pain points and feature requests to the product team
- Validate that new features address real customer problems
- Coordinate customer communications for major releases and known issues
- Monitor customer health metrics and escalate risk accounts to Product Manager and PM

### Goals
- Ensure releases improve customer experience and reduce support burden
- Close the feedback loop between customers and the delivery team
- Build customer confidence through proactive communication and swift issue resolution

### Typical Communication
- Customer feedback summaries and support trend reports shared with Product Manager
- Release communication drafts and customer-facing announcements
- Escalation alerts for high-priority customer impact issues

### Interaction with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Informs PM of operational and customer-facing risks that may affect release decisions |
| Product Manager | Provides customer insights, recurring pain points, and feature request signals to guide prioritization |
| Developers | Helps Developers understand real-world usage scenarios and reproduce customer-reported issues |
| QA/Testing | Contributes real-world test scenarios based on common customer workflows and reported bugs |
| Stakeholders | Provides customer health and satisfaction data to stakeholders through PM communications |

---

## Security / Compliance Representative

### Role Summary
The Security/Compliance Representative ensures that security, privacy, and regulatory compliance considerations are embedded throughout the project lifecycle — from planning through release.

### Responsibilities
- Review designs, architectures, and code changes for security and privacy risks
- Conduct threat modeling and security assessments for new features and integrations
- Define and validate compliance requirements (e.g., GDPR, SOC 2, accessibility standards)
- Maintain security review checklists and sign-off requirements for releases
- Respond to security incidents and coordinate remediation with technical teams

### Goals
- Prevent security vulnerabilities and compliance violations from reaching production
- Shift security left by integrating reviews early in the development lifecycle
- Build team security awareness and embed secure-by-default practices

### Typical Communication
- Security review findings and risk assessments
- Compliance sign-off documentation for releases
- Security incident reports and remediation tracking

### Interaction with Existing Roles
| Role | Interaction |
|---|---|
| Project Manager | Advises on security-driven scope and timeline impacts; escalates high-severity risks to PM |
| Product Manager | Informs compliance-driven feature priorities and constraints; supports privacy-by-design decisions |
| Developers | Reviews implementation for secure coding practices; provides guidance on vulnerabilities and mitigations |
| QA/Testing | Collaborates on security test cases and penetration testing coordination |
| Stakeholders | Reports compliance posture and security risk status through PM for governance and audit purposes |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to [`octoacme-role-interaction-matrix.md`](octoacme-role-interaction-matrix.md) for a consolidated RACI matrix and handoff checklist across all roles.

