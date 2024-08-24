**Purpose:**  
IDS and IPS are security devices used to monitor network traffic for suspicious activities that may indicate a security breach.

### IDS vs. IPS

1. **Intrusion Detection System (IDS):**
   - **Function:** Detects and alerts administrators about potential security breaches.
   - **Placement:** Positioned behind the firewall at the network edge.
   - **Detection Methods:** 
     - **Signature-based:** Matches traffic against known attack signatures.
     - **Anomaly-based:** Identifies deviations from normal network behavior.
   - **Response:** Sends alerts or blocks connections based on predefined rules.
   - **Role:** Monitors internal network traffic for intrusions, providing an additional layer of security.

2. **Intrusion Prevention System (IPS):**
   - **Function:** Goes beyond detection by actively attempting to prevent attacks.
   - **Role:** Acts immediately to block or mitigate detected threats.

### IDS Capabilities and Limitations

- **Capabilities:**
  - Detects attack patterns, abnormal behavior, and policy violations.
  - Can identify various types of intrusions, such as repeated login attempts, unauthorized access, or changes in file size/permissions.

- **Limitations:**
  - IDS/IPS cannot replace logging systems, vulnerability assessment tools, encryption, or antivirus software.
  - Requires proper configuration and planning for effective deployment.
  - Common Mistakes:
    - Incorrect placement of IDS.
    - Ignoring false positives.
    - Lack of a proper response policy.

### IDS Detection Methods

- **Anomaly-based Detection:**  
  Identifies deviations from established network behavior norms.

- **Signature Detection:**  
  Matches traffic patterns to known attack signatures.

- **Behavior-based Detection:**  
  Observes ongoing behaviors and flags those that are out of the ordinary.

- **Structure-based Detection:**  
  Analyzes data structures and identifies malicious activities based on how the data is constructed.

### Best Practices for IDS/IPS

- **Tuning:**  
  Regularly adjust IDS to minimize false positives and negatives.

- **Updating:**  
  Keep IDS signatures up-to-date with the latest threat information.

- **Training:**  
  Ensure network engineers are trained to manage and respond to IDS/IPS alerts effectively.

## Exam
### Question 1

Which of the following types of IDS detection method involves first creating models of possible intrusions and then comparing these models with incoming events to make a detection decision?

- Signature recognition
- Not-use detection
- Protocol anomaly detection
- Anomaly detection

### Question 2

James, a security team member, was assessing the security across organizational assets. He identified sudden fluctuations in the bandwidth consumption and repeated login attempts being made from remote hosts.

- Physical intrusions
- File system intrusions
- System intrusions
- Network intrusions