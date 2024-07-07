- **MAC Flooding:**
  - Fills the MAC table with entries until full.
  - Switch acts like a hub when the MAC table is full.
  - In a hub, all traffic is repeated to all ports.
  - In a switch, traffic is only sent to the intended port.
  - Using tools like macof, attackers flood the switch with MAC entries.
  - This allows attackers to see all traffic on the network.
  
- **DHCP Starvation:**
  - Denial of service attack.
  - Fakes multiple requests to the DHCP server.
  - Floods the server until all IP addresses are leased.
  - Prevents new devices from getting an IP address and network access.

- **ARP Spoofing:**
  - ARP requests are broadcasted to find the MAC address associated with an IP address.
  - Attackers respond with their own MAC address, spoofing the legitimate user.
  - Redirects traffic to the attacker's machine.
  - Tools: ARPspoof, BetterCAP, Ettercap, dsniff, MITMf, Arpoison.

- **MAC Spoofing/Duplication:**
  - Attacker changes their MAC address to match an allowed MAC address.
  - Allows unauthorized access to a network.
  
- **DNS Poisoning:**
  - Improper entries are inserted into the DNS table.
  - Legitimate website IPs are replaced by attacker's IP.
  - Leads to users accessing fake sites, potentially downloading malware.

- **Tools for Sniffing:**
  - **Wireshark:**
    - Primary tool for sniffing.
    - Captures and browses traffic on the computer.
    - Allows filtering and detailed inspection of frames, packets, and payloads.
  - Other Tools:
    - SteelCentral Packet Analyzer.
    - Capsa Network Analyzer.
    - Observer Analyzer.
    - Various terminal mode packet sniffers for Linux.