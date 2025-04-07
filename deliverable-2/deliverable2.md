# Deliverable 2: Functional and System Requirements

---

## 1. Introduction

This deliverable translates the findings and goals from Deliverable 1 into clear, actionable **functional and system requirements**. These requirements aim to support the development of a real-time environmental monitoring system, ensuring it meets the needs of stakeholders such as residents, environmental agencies, researchers, and policymakers. All requirements are designed to be SMART (Specific, Measurable, Achievable, Realistic, Time-bound) and reflect best practices for requirement elicitation.

---

## 2. Functional Requirements

The functional requirements describe what the system should do. These are derived directly from stakeholder needs and the high-level features outlined in Deliverable 1.

| ID | Requirement Description |
|----|--------------------------|
| FR1 | The system shall collect real-time data from air quality sensors (PM2.5, CO2, NO2, Ozone) every 5 seconds. |
| FR2 | The system shall collect water quality data (pH, turbidity, TDS) from installed sensors in key water sources. |
| FR3 | The system shall store all sensor data in a cloud-based time-series database for future retrieval and analysis. |
| FR4 | The system shall provide a web-based dashboard with map visualization and trend graphs for pollution levels. |
| FR5 | The system shall allow users to set thresholds and receive real-time alerts via email or SMS when pollution levels exceed safe limits. |
| FR6 | The system shall include user authentication and role-based access control (e.g., Public, Researchers, Admin). |
| FR7 | The system shall allow authorized users to export historical data in CSV and PDF formats. |
| FR8 | The system shall maintain uptime of 99% and handle at least 100 concurrent users without performance degradation. |


---

