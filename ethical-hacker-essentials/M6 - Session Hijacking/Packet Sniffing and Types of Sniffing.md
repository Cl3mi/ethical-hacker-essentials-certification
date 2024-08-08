  - Packet sniffing involves capturing and analyzing network traffic.
  - It's essential to understand host-to-host communication and Ethernet frames.
  - Ethernet frames consist of preamble, destination and source MAC addresses, protocol information, and payload.

- **Ethernet Frame Components**:
  - **Preamble**: Signals the start of an Ethernet frame.
  - **Destination & Source MAC Addresses**: Identifies the sender and receiver.
  - **Protocol Information**: Indicates the type of data carried.
  - **Payload**: Contains the actual data, such as TCP segments and their payloads.

- **Packet Sniffer Functionality**:
  - Captures and analyzes frames and their contents.
  - Can reveal details like IP addresses, TCP handshakes, and the data being transmitted.

- **Promiscuous Mode**:
  - A NIC in promiscuous mode captures all frames it encounters, regardless of the destination MAC address.

- **Types of Sniffing**:
  - **Passive Sniffing**: Simply listens to network traffic without interfering.
  - **Active Sniffing**: Involves injecting traffic into the network to gather more information.

- **Techniques for Active Sniffing**:
  - **ARP Spoofing**: Redirects traffic by poisoning the ARP cache.
  - **MAC Flooding**: Overloads a switch’s MAC table, causing it to act like a hub.
  - **DNS Poisoning**: Corrupts the DNS cache to redirect traffic.
  - **DHCP Attacks**: Manipulates DHCP to alter network configurations.

- **Sniffing Vulnerabilities in Protocols**:
  - **Telnet**: Transmits data in plain text, including commands and passwords.
  - **HTTP**: Not encrypted, unlike HTTPS.
  - **Email Protocols (POP, IMAP, SMTP)**: Often lack encryption.
  - **FTP**: Transmits files in clear text.

- **Attack Process**:
  - **Step 1**: Connect to a network port, such as in a conference room.
  - **Step 2**: Identify the target machine.
  - **Step 3**: Redirect traffic intended for the target to the attacker.
  - **Step 4**: Use discovery tools to understand network topology.
  - **Step 5**: Use ARP spoofing to poison the victim’s machine and redirect traffic.

- **Common Vulnerable Protocols**:
  - Telnet, HTTP, POP, IMAP, SMTP, NNTP, and FTP.
  - These protocols are often unencrypted and susceptible to sniffing.