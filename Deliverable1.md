# Deliverable 1: Research and Requirements Foundation

**Project Title:** Environmental Monitoring System – Tracking Air and Water Quality in the Region 
**Team Role:** Yash Shah - Business Analyst & Scrum Master | Yash Patel - Research Analyst
**Course/Program:** Software Engineering Principles | SENG8091 - Winter 2025 - Section 1
**Institution:** Conestoga College 
**Date:** 03rd April 2025

---

## 2. Problem Statement

Environmental degradation has become a critical global concern. Air and water pollution not only harm ecosystems but also directly impact public health and safety. In many regions, the lack of localized, real-time monitoring of environmental quality leads to:

- Delayed responses to hazardous conditions
- Poor community awareness
- Insufficient data for scientific or governmental use

Despite the availability of some public data (e.g., via national agencies), it is often:

- Not available in real-time
- Difficult to interpret by non-specialists
- Missing from remote or underserved areas

---

## 3. Initial Hypotheses

| Hypothesis | Justification |
|-----------|----------------|
| **H1:** Current environmental monitoring systems are inadequate for real-time, location-specific tracking. | Most systems rely on central stations that update periodically and don’t provide hyperlocal insights. |
| **H2:** General public lacks easy access to clean, understandable environmental quality data. | Existing platforms are designed for scientific use and lack user-friendly interfaces or alert systems. |
| **H3:** Implementing a modern, sensor-driven monitoring and alert system will help communities and governments make proactive decisions. | Evidence from smart city implementations shows a strong correlation between real-time data and better policy/action. |

---

## 4. Research and Literature Review

### A. Environmental Impact

- WHO: Air pollution contributes to 7 million premature deaths annually[1].
- UNESCO: Over 2 billion people globally consume contaminated water[2].
- Environmental Performance Index (Yale University, 2022): Identifies lack of data transparency and digital monitoring as key weaknesses[3].

### B. Canadian Context

- Environment and Climate Change Canada (ECCC): Over 65% of water stations are more than 20 years old[4].
- OpenAQ and AirNow APIs: Provide useful data but require integration and interpretation[5][6].

### C. Industry Benchmarking

- Smart cities (Singapore, Copenhagen, Amsterdam): Use localized sensors and public dashboards[7].
- Toronto pilot dashboard: Supported better policy formation[8].
- IoT sensors (e.g., MQ135, TDS Meter): Affordable and easy to integrate into cloud platforms[9][10].

---

## 5. Stakeholder Analysis

| Stakeholder Group | Needs | Goals | Concerns |
|-------------------|-------|-------|----------|
| Local Residents | Real-time air/water data | Protect health, plan outdoor activities | Data reliability, ease of use |
| Environmental Agencies | Accurate long-term records | Ensure compliance, alert systems | Sensor calibration, maintenance |
| Researchers & Universities | Historical and real-time datasets | Conduct analysis, publish insights | Open data access |
| Policy Makers & Planners | Data visualizations, trend reporting | Develop environmental policies | Interpretation of complex data |
| Tech Developers | APIs, sensor feeds | Build tools, integrate solutions | Integration standards |

---

## 6. System Vision and Concept

### Platform Overview

The system will include three major modules:

1. **Sensor Layer:** Air (PM2.5, PM10, CO2, NO2, Ozone) and water sensors (pH, turbidity, TDS).
2. **Data Collection & Cloud Storage:** Real-time data sent to cloud databases.
3. **Web-Based Dashboard & Alert System:** Visualization, trends, maps, alerts.

### User Personas

- *Tony*: Local resident who wants alerts for poor air quality.
- *Steve*: Researcher analyzing water quality trends.
- *Shang-Chi*: Municipal officer reviewing data trends for policy.
