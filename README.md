# Incident Lifecycle Automation in ServiceNow

##  Project Overview

**Incident Lifecycle Automation in ServiceNow** demonstrates the end-to-end management of IT incidents using ServiceNow IT Service Management (ITSM).

The project follows a **Corporate VPN Connectivity Issue** from incident creation and classification through troubleshooting, reassignment, escalation, resolution, and knowledge creation. It highlights how ServiceNow helps support teams manage incidents systematically and maintain clear records throughout the incident lifecycle.

##  Project Objectives

- Create and manage incident records in ServiceNow.
- Classify incidents based on category, impact, and urgency.
- Associate incidents with relevant services and configuration items.
- Use Knowledge Management to support incident investigation.
- Reassign incidents to the appropriate support groups.
- Track SLA information and incident progress.
- Create and manage child incidents where required.
- Document root causes, work notes, and resolution details.
- Create knowledge articles from resolved incidents.
- Validate incident status and resolution information.

##  Technologies and Modules

| Technology / Module | Purpose |
|---|---|
| ServiceNow | IT service management platform |
| Incident Management | Incident creation, tracking, and resolution |
| Service Operations Workspace | Incident handling and agent workspace |
| Knowledge Management | Troubleshooting guidance and knowledge reuse |
| SLA Management | Monitoring incident service-level commitments |
| Configuration Management | Associating incidents with services and configuration items |

##  Incident Lifecycle Workflow

The project uses a Corporate VPN Connectivity Issue to illustrate the following workflow:

```text
Incident Creation
       ↓
Incident Classification
       ↓
Service and CI Association
       ↓
Knowledge-Based Troubleshooting
       ↓
Reassignment to Network Support
       ↓
Level 2 Investigation
       ↓
Awaiting Change (if required)
       ↓
Child Incident Creation (if required)
       ↓
Incident Resolution
       ↓
Knowledge Article Creation
       ↓
Final Validation
```

*Note: Conditional steps, such as awaiting a change or creating a child incident, apply only when required by the scenario.*

##  Repository Structure

```text
Incident-Lifecycle-Automation-in-ServiceNow/
│
├── Screenshots/
│   └── Implementation evidence
│
├── Ideation Phase.pdf
├── Requirement Analysis.pdf
├── Project Design Phase.pdf
├── Project Planning Phase.pdf
├── Project Development Phase.pdf
├── Final Project Documentation.pdf
│
└── README.md
```

##  Project Evidence

The [`Screenshots`](Screenshots/) folder contains screenshots documenting the ServiceNow implementation and relevant project stages.

These screenshots provide visual evidence of the incident workflow and configuration completed during the project.

##  Project Documentation

The following documents describe the project from planning to implementation:

- [Ideation Phase](Ideation%20Phase.pdf)
- [Requirement Analysis](Requirement%20Analysis.pdf)
- [Project Design Phase](Project%20Design%20Phase.pdf)
- [Project Planning Phase](Project%20Planning%20Phase.pdf)
- [Project Development Phase](Project%20Development%20Phase.pdf)
- [Final Project Documentation](Final%20Project%20Documentation.pdf)

##  Expected Outcomes

The project demonstrates how ServiceNow can support a structured incident management process by helping teams:

- Maintain consistent incident records and status tracking.
- Improve incident assignment and escalation visibility.
- Use knowledge articles to support troubleshooting.
- Record investigation findings and resolution details.
- Improve collaboration between support teams.
- Maintain better visibility into incident progress and SLA information.

##  Future Enhancements

- Automate incident assignment using configurable business rules or flows.
- Configure automated notifications for assignment changes and SLA risks.
- Develop dashboards to monitor incident trends and resolution performance.
- Expand automated testing for incident lifecycle scenarios.

##  Author

**Sai Sudiksha Kolla**

[GitHub Repository](https://github.com/kssudiksha8/Incident-Lifecycle-Automation-in-ServiceNow)

---

*This project was developed for learning and demonstrating ServiceNow ITSM incident management concepts.*
