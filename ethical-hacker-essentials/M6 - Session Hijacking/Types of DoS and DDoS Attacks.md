
- **Denial-of-Service (DoS)**:
  - Floods a service (e.g., web server, DNS server) with so much data that it becomes unavailable.
  - Blocks legitimate users from accessing the service.
  
- **Distributed Denial-of-Service (DDoS)**:
  - Involves multiple zombie computers (infected with botnet software).
  - Coordinates to flood a target with traffic from various sources simultaneously.

- **Types of DDoS Attacks**:
  - **UDP Flood**: Overwhelms a target with UDP packets, rendering legitimate services inaccessible.
  - **ICMP Flood**: Floods the target with ICMP echo requests (ping), exhausting its resources.
  - **Ping of Death**: Sends oversized ICMP packets to crash vulnerable systems.
  - **Smurf Attack**: Spoofs victim's IP address to send ICMP echo requests to multiple hosts, flooding victim with responses.
  - **SYN Flood**: Sends numerous SYN requests without completing the TCP handshake, exhausting resources and preventing legitimate connections.
  - **Fragmentation Attack**: Floods target with fragmented packets, overwhelming its ability to reassemble them.
  
- **Other DDoS Techniques**:
  - **Permanent DoS Attack**: Physically damages hardware or firmware to render it unusable.
  - **Peer-to-Peer Attack**: Targets peer-to-peer networks, exploiting connections to overwhelm systems.
  - **Distributed Reflection DoS (DRDoS)**: Uses intermediaries to amplify and reflect attack traffic, complicating tracing back to the original attacker.

These attacks aim to disrupt services, deny access to legitimate users, and in some cases, cause permanent damage to systems or hardware.