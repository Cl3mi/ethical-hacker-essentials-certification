**Purpose:**  
Firewalls are essential for filtering and monitoring incoming and outgoing network traffic, providing a critical layer of security.

### Types of Firewalls

1. **Hardware Firewalls:**
   - **Definition:** Dedicated devices or routers with firewall capabilities.
   - **Function:** Perform packet filtering to exclude unwanted traffic from the network.
   - **Examples:** SonicWall, Netgear, D-Link.

2. **Software Firewalls:**
   - **Definition:** Installed on individual computers to filter traffic for that specific system.
   - **Function:** Protects the host system, not the entire network.
   - **Examples:** Windows Firewall, BullGuard, IP tables (Linux).

### Additional Firewall Technologies and Capabilities

- **Stateful Multi-Layer Inspection:**
  - **Function:** Examines traffic across multiple OSI layers, including packet filtering, session rules, and application-level commands.

- **Application Proxies:**
  - **Function:** Act as intermediaries between applications and the network, controlling traffic based on application protocols.

- **Network Address Translation (NAT):**
  - **Function:** Maps private IP addresses to public IP addresses, allowing multiple devices to share one public IP.

- **Virtual Private Networks (VPNs):**
  - **Function:** Create secure, encrypted connections over the internet for remote access to private networks.

### Next-Generation Firewalls (NGFW)

- **Features:**  
  - Combine multiple firewall technologies: packet filtering, session monitoring, application-level inspection, NAT, and VPNs.
  - Provide advanced security features.
  
- **Considerations:**  
  - Require proper configuration and expertise for effective management.

## Exam:
Question 1

Which of the following firewall technologies works at the session layer of the OSI model or the TCP layer of TCP/IP model and filters the traffic based on specified session rules?

- Application proxy
- Network address translation
- Packet filtering
- **Circuit-level gateway**
	- or Virtual Private Network

### 2.

Question 2

Which of the following information allows the firewall to check whether the packet has a SYN, ACK, or other bits set for connecting with the destination host?

- Source IP address
- Protocol in use
- Destination TCP/UDP port
- **TCP code bits**
	- checks if packet has SYN, ACK, or other bits sets for connecting