**Bluetooth Overview:**
- **Bluetooth** is a short-range communication technology used for connecting devices wirelessly, such as headsets and watches.
- It operates within a personal area network (PAN) and communicates over short distances with low power.
- **Bluetooth Stack:** Includes middleware protocols, hardware communication (HCI), and transport protocols.

**Bluetooth Modes:**
- **Discoverable:** Device responds to all inquiries and can be detected by other devices.
- **Limited Discoverable:** Device is visible only for a limited time.
- **Non-Discoverable:** Device does not respond to inquiries, making it invisible to other devices.
- **Pairing Modes:** Non-pairable mode rejects pairing requests, while non-discoverable and non-pairing modes are considered safest.

**Bluetooth Security Evolution:**
- Bluetooth security has improved over time, reducing vulnerabilities from earlier versions where connection codes were weak.

**Common Bluetooth Attacks:**
1. **Bluesmacking:** A denial of service (DoS) attack that overwhelms the device with data, causing it to crash.
2. **Bluejacking:** Sending unsolicited messages to a Bluetooth device, often appearing as unexpected notifications.
3. **Bluesnarfing:** Stealing information from a Bluetooth device, such as contacts or personal data.
4. **Bluesniffing:** Collecting information about nearby Bluetooth devices, similar to wardriving for Wi-Fi.
5. **Bluebugging:** Exploiting a device to listen in on conversations or take control of functions.
6. **BluePrinting:** Gathering detailed information about a Bluetooth device, akin to footprinting in hacking.
7. **Btlejacking:** Attacking BLE (Bluetooth Low Energy) devices to bypass security and listen in.
8. **KNOB Attack:** Exploiting a Bluetooth vulnerability to eavesdrop on communication by intercepting data.
9. **MAC Spoofing:** Changing the MAC address to intercept data meant for another Bluetooth device.
10. **Google MitM (Man-in-the-Middle):** Involves sniffing and monitoring the network to impersonate and intercept communications between devices.

**Bluetooth Threats:**
- **Data Leakage:** Includes leaking calendars, address books, and SMS.
- **Swatting:** False emergency reports sent via compromised SMS, leading to SWAT team interventions.
- **Bugging Devices:** Unauthorized control of a phone to make calls or record conversations.
- **Financial Losses:** Unauthorized calls or messages can lead to high bills.
- **Worms:** Malware that spreads via Bluetooth to infect other devices.
- **Social Engineering:** Tricks users into lowering security settings.
- **Protocol Vulnerabilities:** Exploiting weaknesses in pairing and communication protocols to steal data or execute malicious actions.

**Bluetooth Attack Tools:**
- **BluetoothView:** Lists Bluetooth devices and their details.
- **BlueZ, BtleJack, BTCrawler, BlueScan:** Various tools for discovering and hacking Bluetooth devices.
- **Bluetooth Scanner:** Identifies nearby Bluetooth devices.
