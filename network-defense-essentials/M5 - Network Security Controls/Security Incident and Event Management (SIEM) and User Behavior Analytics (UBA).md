### SIEM (Security Incident and Event Management)

**What is SIEM?**
- **Functionality:** SIEM systems provide real-time monitoring, tracking, and management of security incidents across an enterprise network.
- **Purpose:** Collects logs and event data from various devices and systems to identify and analyze security threats.

**Core Features:**
- **Real-Time Monitoring:** Tracks suspicious behavior across user activities, network traffic, and device operations.
- **Integration:** Combines Security Information Management (SIM) and Security Event Management (SEM) for comprehensive monitoring.
- **Data Handling:** Aggregates, normalizes, stores, and analyzes logs from various sources.
- **Alerts and Reporting:** Generates real-time alerts, reports, and dashboards for incident response and monitoring.

**SIEM Architecture:**
- **Components:** Includes operating systems, applications, servers, firewalls, antivirus, IDS/IPS, routers, switches, and VPNs.
- **Data Collection:** Collects event data from various sources, such as servers (e.g., Microsoft Server 2019 Event Viewer), firewalls, routers, and switches.
- **Normalization:** Standardizes data from different vendors into a common format to facilitate analysis.
- **Storage and Analysis:** Stores large volumes of normalized data in databases (e.g., Oracle, SQL Server, MySQL) for long-term retention and analysis.

**Popular SIEM Solutions:**
- **Splunk:** Known for its enterprise capabilities in detecting and responding to security threats.
- **ArcSight, IBM QRadar, AlienVault (OSSIM), FortiSIEM, SolarWinds:** Other notable SIEM solutions for various security needs.

### User Behavior Analytics (UBA) and User and Entity Behavior Analytics (UEBA)

**UBA (User Behavior Analytics):**
- **Purpose:** Monitors and analyzes user behavior to identify deviations from normal patterns, which can indicate potential security threats or fraud.
- **Benefits:** Helps detect malicious and negligent insider threats, financial fraud, and other internal risks.
- **Functionality:** Analyzes large volumes of user data, monitors geo-location for logins, and tracks privileged accounts.

**UEBA (User and Entity Behavior Analytics):**
- **Extended Scope:** Includes analysis of not only user behavior but also entities such as applications, programs, and specific components like DLLs.
- **Capabilities:** Uses AI and machine learning to identify anomalies and threats beyond user behavior alone.
- **Tools:** Includes solutions such as Exabeam Advanced Analytics, LogRhythm UEBA, Dtex Systems, and Gurucul Risk Analysis (GRA).

**General Considerations:**
- **AI/ML Integration:** Modern UBA/UEBA tools often incorporate AI and machine learning for enhanced threat detection and response.
- **Implementation:** Provides insights for security teams to understand and secure user and entity behaviors within an organization.

## Exam
Which of the following tools is an analytics-driven SEIM solution that automates the collection, indexing, and alerting of real-time machine data that are critical to an organization's operations?

- OSRFramework
- **Splunk Enterprise**
- Burp Suite
- Netcraft

The Splunk Enterprise Security (ES) is an analytics driven SEIM solution that provides you with what you need to detect and respond to internal and external attacks quickly. It automates the collection, indexing, and alerting of real-time machine data that are critical to an organization's operations.

### 2.

Question 2

Identify the SIEM function that stores logged data in a central repository for long periods to meet compliance and regulatory requirements and for conducting forensic analysis, investigation, and internal audits.

- Object access auditing
- System and device log monitoring
- **Log retention**
- Data aggregation

SIEM stores logged data in a central repository for long periods to meet compliance and regulatory requirements and for conducting forensic analysis, investigation, and internal audits.