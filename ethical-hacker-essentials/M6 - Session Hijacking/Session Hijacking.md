
- **Definition and Impact:**
  - Session hijacking involves taking over a valid TCP communication session between two hosts, allowing attackers to intercept data, perform identity theft, and potentially engage in fraud.
  - Victims may not immediately notice the hijacking, as the attacker can seamlessly continue the session.

- **Vulnerabilities Exploited:**
  - Successful session hijacking often exploits factors such as absence of account lockout mechanisms, weak session ID algorithms, or infinite timeouts on session IDs.
  - TCP/IP protocols' predictability in session establishment and management can be leveraged by attackers.

- **Countermeasures:**
  - **Encryption:** Encryption is crucial to protect against session hijacking, ensuring that intercepted data is unreadable to unauthorized parties.
  - **Network Monitoring and Packet Analysis:** Monitoring network traffic and analyzing packet sequences can help detect anomalies that indicate session hijacking attempts.
  - **Security Measures Across OSI Layers:** Understanding and securing layers 3 (network) and 4 (transport) of the OSI model are essential, as session hijacking often targets these layers.
  - **Avoidance of Unsafe Practices:** Avoiding unnecessary functions like gets and strcpy reduces buffer overflow risks, which are potential entry points for session hijackers.

- **Process of Session Hijacking:**
  - Attackers place themselves between the victim and the target, monitoring and intercepting TCP segments.
  - They predict sequence numbers to desynchronize the session, redirecting subsequent communication to their own IP address.
  - Once hijacked, attackers can inject their own commands or data into the session, gaining unauthorized control.

- **Types of Session Hijacking:**
  - **Passive Hijacking:** Attackers observe and download information from the session without altering its course.
  - **Active Hijacking:** Attackers seize control of the session, manipulating its flow and content to their advantage.

- **OSI Model Layers and Hijacking:**
  - **Layer 3 (Network Layer):** Involves intercepting packets at the IP level, manipulating routing, and possibly redirecting traffic.
  - **Layer 4 (Transport Layer):** Concerns the hijacking of TCP and UDP sessions, exploiting protocol weaknesses.
  - **Layer 7 (Application Layer):** Involves gaining control over specific applications or services, such as HTTP sessions, by exploiting session IDs.

- **Difference Between Spoofing and Hijacking:**
  - **Spoofing:** Involves impersonating another entity by falsifying IP or MAC addresses obtained through sniffing.
  - **Hijacking:** Occurs when an active session is taken over by the attacker, giving them control and ownership of the session.
