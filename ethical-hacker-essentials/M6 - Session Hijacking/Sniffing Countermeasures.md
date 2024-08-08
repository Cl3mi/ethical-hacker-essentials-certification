- **Restricting Physical Access:**
  - Limit access to network ports in public areas like conference rooms and front desks.
  - Ensure unauthorized individuals cannot plug into the network.

- **End-to-End Encryption:**
  - Crucial for both wireless and wired connections to protect data.

- **Permanent ARP Cache Entries:**
  - Use static ARP entries for the gateway to prevent spoofing.
  - In the system image rollout, include static MAC and gateway addresses.

- **Static IP Addresses and ARP Tables:**
  - Similar to static ARP entries, using static IPs can enhance security.
  
- **Turn Off Network Identification Broadcasts:**
  - Prevents attackers from discovering network details via sniffing tools.

- **Restrict Network to Authorized Users:**
  - Ensures only verified users can access the network.

- **Detecting Sniffers on the Network:**
  - **NIC in Promiscuous Mode:**
    - Detect by sending a ping with the wrong MAC address.
    - A machine in promiscuous mode will respond.
  - **DNS Method:**
    - Machines in promiscuous mode often perform reverse DNS lookups.
    - Identify suspicious reverse lookups to detect sniffers.
  - **ARP Method:**
    - Machines in promiscuous mode cache incorrect ARP information and respond to pings.
    - Use ARP probes to identify such machines.
  - **Tools:**
    - Microsoft and Nmap scripts can detect sniffers on the network.

- **Summary of Detection Methods:**
  - **Ping with Wrong MAC Address:** Checks for responses from NICs in promiscuous mode.
  - **Reverse DNS Lookups:** Identifies machines performing unexpected lookups.
  - **ARP Probes:** Detects machines caching incorrect ARP data.
  - **Detection Tools:** Use specialized software to scan for sniffers on the subnet.