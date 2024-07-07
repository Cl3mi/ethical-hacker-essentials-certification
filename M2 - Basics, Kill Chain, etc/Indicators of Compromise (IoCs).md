- **Indicators of Compromise (IoCs):**
  - **Definition:** Clues or forensic data that indicate potential malicious activity, intrusions, or ongoing attacks.
  - **Purpose:** Provide valuable information for threat detection, intelligence gathering, and response to threats.

- **Types of IoCs:**
  - **Email Indicators:** Sender's email address, subject, attachments, and header information. Used to identify and block malicious emails.
  - **Network Indicators:** URLs, domain names, IP addresses, command and control server activity. Used in network protection systems to block malicious traffic.
  - **Host-Based Indicators:** Infected registry keys, mutex, DLLs, file hashes. Used in endpoint protection to quarantine or delete malicious files.
  - **Behavioral Indicators:** Unusual activity such as PowerShell or remote command execution in environments with predictable behavior patterns.

- **Usage of IoCs:**
  - **Detection:** Continuous monitoring to identify IoCs and detect threats.
  - **Response:** Use IoCs in the forensic process to analyze and stop threats.
  - **Prevention:** Feed IoCs into security systems (e.g., endpoint protection, intrusion detection) to block future attacks.

- **Key Takeaway:**
  - IoCs are critical for defending networks by identifying and blocking malicious activity based on different types of indicators.