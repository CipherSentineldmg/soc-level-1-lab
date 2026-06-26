# SOC Level 1 Lab – Development Progress

## Project Goal

Build a recruiter-level Security Operations Center (SOC) dashboard and mini-SIEM entirely in HTML, CSS and JavaScript to demonstrate cybersecurity, programming and incident response concepts.

---

# Current Status

**Version:** v0.5.0
**Progress:** Level 5 / 10 Complete

---

# Completed Features

## Level 1 – Event Generation Engine

* Created a simulated SIEM event engine.
* Added random INFO, WARNING and CRITICAL events.
* Implemented dynamic Threat Level calculation.
* Added event timestamps and log sources.

### Skills Demonstrated

* JavaScript modules
* State management
* Event simulation

---

## Level 2 – Detection Rules Engine

* Implemented brute-force attack detection.
* Added automated rule triggering.
* Generated security alerts based on thresholds.

### Skills Demonstrated

* Detection engineering
* Rule-based security monitoring
* Incident generation

---

## Level 3 – Correlation Engine

* Added event history tracking.
* Implemented multi-event correlation.
* Created correlated incidents.

### Skills Demonstrated

* SIEM correlation logic
* Incident detection
* Security analytics

---

## Level 4 – System Monitoring

* Added System Health module:

  * CPU usage
  * Memory usage
  * System load
* Added incident management panel.
* Implemented incident history.

### Skills Demonstrated

* Dashboard design
* Monitoring systems
* Incident lifecycle management

---

## Level 5 – Log Search & Filtering

* Added log search functionality.
* Added filtering by severity:

  * INFO
  * WARNING
  * CRITICAL
  * ALL
* Improved dashboard usability.

### Skills Demonstrated

* DOM manipulation
* Search algorithms
* User experience design

---

# Threat Intelligence Module

Implemented:

* Simulated APT groups.
* Dynamic threat scores.
* Latest attack feed.
* Threat intelligence updates.

Included groups:

* Lazarus Group
* APT28
* APT29

### Skills Demonstrated

* Threat Intelligence concepts
* Cyber threat simulation
* Data visualization

---

# Current Architecture

```text
soc-level-1-lab/
├── assets/
├── css/
├── docs/
├── js/
│   ├── app.js
│   ├── engine.js
│   ├── threatIntel.js
│   └── ui.js
├── logs/
├── pages/
├── projects/
├── scripts/
└── README.md
```

---

# Next Development Goals

## Level 6 – Real-Time Dashboard

* Threat timeline graph
* Event timeline
* Toast notifications
* Dashboard widgets

## Level 7 – Advanced Query Engine

* source:
* level:
* AND / OR filtering

## Level 8 – Export Features

* JSON export
* CSV export
* Incident reports

## Level 9 – Advanced SOC Simulation

* MITRE ATT&CK mapping
* Playbooks
* Alert enrichment

## Level 10 – Recruiter-Level SIEM

* Persistent storage
* Multi-page dashboard
* Fake backend/API
* Production-style architecture

---

# Technologies Used

* HTML5
* CSS3
* JavaScript (ES Modules)
* Git
* GitHub

---

# Author

Charles Arsenault-Patry

Project in active development.
