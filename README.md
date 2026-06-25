# SOC LEVEL 1 LAB

A real-time SOC (Security Operations Center) simulation system built with vanilla JavaScript.  
It emulates core blue team workflows such as event monitoring, threat scoring, and cyber threat intelligence aggregation.

---

## 🎯 Purpose

This project was built to demonstrate practical understanding of:

- SOC workflows (event detection → analysis → response)
- Threat intelligence concepts (APT groups, attack patterns)
- Real-time system design using modular JavaScript
- UI-driven security monitoring dashboards

This is not a data-driven SOC, but a **behavioral simulation system** focused on realism of structure and dynamics.

---

## 🧠 System Architecture

The system is built around 3 core modules:

---

## ⚙️ Core Modules

### 🧠 Engine
- Generates randomized security events
- Classifies events into INFO / WARNING / CRITICAL
- Maintains system-wide metrics (event counts, threat level)

### 🛡️ Threat Intelligence Module
- Simulates APT groups (e.g. Lazarus Group, APT28, APT29)
- Assigns dynamic risk scores
- Updates activity levels in real time
- Provides top threat rankings

### 🖥️ UI Layer
- Real-time log visualization
- Security metrics dashboard
- Threat level indicator
- Threat intelligence display panel

---

## 📊 Features

- Real-time event generation loop
- Dynamic threat level calculation (0–100)
- Rolling security event log
- Top 3 threat actor ranking system
- Simulated cyber threat intelligence feed
- Modular ES6 architecture

---

## 🧬 Threat Intelligence Model

The simulation includes structured threat actor profiles inspired by real-world cybersecurity frameworks (e.g. MITRE ATT&CK):

Example groups:

- Lazarus Group
- APT28 (Fancy Bear)
- APT29 (Cozy Bear)

Each actor includes:
- Risk score
- Last known activity
- Simulated attack techniques (TTP concepts)

---

## 🧱 Tech Stack

- Vanilla JavaScript (ES Modules)
- HTML5
- CSS3
- DOM-based real-time rendering

No frameworks were used in order to demonstrate raw system design and control over architecture.

---

## 🚀 How it works

1. `Engine` generates a security event every 2.5 seconds
2. Event is classified and updates global metrics
3. `ThreatIntel` updates APT group risk levels
4. `UI` renders updated system state in real time

---

## 🖼️ Future Improvements

- Integration with real threat intelligence feeds (CISA / MITRE / RSS)
- Interactive incident investigation panel
- Timeline-based attack visualization
- Graph-based threat network mapping
- Persistence layer (local storage or backend API)

---

## 🎓 Learning Outcomes

This project demonstrates:

- Modular JavaScript architecture
- Real-time UI state management
- Simulation-based system design
- Cybersecurity conceptual modeling
- Event-driven programming

---

## 📌 Status

Work in progress – core SOC simulation fully functional.  
System is actively evolving toward a full Cyber Threat Intelligence dashboard.

---

## 👤 Author

Built as part of a cybersecurity learning and portfolio development process focused on SOC analysis and system simulation design.
