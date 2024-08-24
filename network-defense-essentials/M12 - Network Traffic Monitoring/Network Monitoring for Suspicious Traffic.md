## Network Monitoring with WireShark

### Overview of WireShark

- **WireShark** is a widely used network monitoring tool.
  - It operates on almost any operating system.
  - It can examine a wide range of protocols.
  - It captures and analyzes network traffic.

### Key Features of WireShark

- **Packet Analysis**:
  - Displays packets captured by the network interface card (NIC).
  - Allows inspection of individual frames, packets, and TCP segments.
  - Displays the payload data if not encrypted.

- **Filtering**:
  - Essential for managing large volumes of captured data.
  - Use the **filter toolbar** to refine the traffic displayed.
  - Examples of filters:
    - **Port Filtering**: For example, filtering by port 25 to find email servers.
    - **Protocol and Service Identification**: Filters to identify specific services, like SMTP on port 25 or HTTP on port 80.
    - **TCP Stream Analysis**: Examine the entire stream of data for patterns, such as user names and passwords.

### Analysis Techniques

- **Content-Based Signature Analysis**:
  - Involves examining the payload of packets to identify suspicious content.
  - Looks for specific text strings that indicate potential attacks.

- **Context-Based Signature Analysis**:
  - Analyzes packet headers rather than payloads.
  - Examines source and destination IP addresses, ports, protocols, checksums, and other header details.
  - Identifies anomalies like unexpected geographical locations.

- **Atomic Signature-Based Analysis**:
  - Focuses on detecting signatures in individual packets.
  - Sometimes used in conjunction with other methods for more comprehensive analysis.

- **Composite Signature-Based Analysis**:
  - Requires analyzing a series of packets over time.
  - Useful for detecting patterns in large data flows.
  - Examples include detecting ICMP flooding attacks.

### Practical Use Cases

- **Banner Grabbing**:
  - Identifies the type and version of services running on specific ports.
  - Example: Filtering for port 25 to find an email server and its details.

- **Stealth Scanning Detection**:
  - Detects SYN scans or stealth scans.
  - Look for TCP reset flags in responses during scans to identify stealth activity.

- **FTP Traffic Monitoring**:
  - Filter by FTP protocol (ports 20 and 21) to analyze FTP traffic.
  - Allows inspection of FTP payloads, such as usernames and passwords.

### Summary

- WireShark is a versatile tool for monitoring and analyzing network traffic.
- It provides detailed insights into traffic patterns and potential security threats.
- Effective use involves filtering and analyzing both packet headers and payloads to detect suspicious activities.