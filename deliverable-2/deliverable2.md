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

## 3. System Requirements

System requirements describe the technical environment and constraints necessary for the system to function.

### 3.1 Hardware Requirements

- Air Quality Sensors: MQ135, DHT22, and NO2/O3-specific sensors [9]
- Water Sensors: TDS Meter, pH sensor, turbidity sensor
- Microcontroller: Arduino/ESP32 or Raspberry Pi with GSM/Wi-Fi module
- Server: Cloud-based hosting on AWS IoT Core or Firebase [10]

### 3.2 Software Requirements

- Backend: Node.js or Python Flask for API development
- Frontend: React.js or Angular with Chart.js for visualization
- Database: Firebase Realtime DB / InfluxDB for time-series data
- Mobile App (Optional): Flutter or React Native
- Notification Service: Twilio (SMS) and SendGrid (email)

### 3.3 Non-Functional Requirements

| ID | Description |
|----|-------------|
| NFR1 | The system shall refresh sensor readings every 5 seconds. |
| NFR2 | The system shall ensure 99% uptime during operational hours. |
| NFR3 | The web dashboard shall load within 3 seconds for 90% of users. |
| NFR4 | The system shall support localization (English/French). |
| NFR5 | The system shall encrypt data in transit and at rest using HTTPS and AES-256. |

---


