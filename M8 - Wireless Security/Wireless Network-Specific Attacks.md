1. **Rogue Access Points:**
   - Attackers set up fake access points mimicking legitimate networks like "McDonald's free Wi-Fi" or "XYZ Corp visitor Wi-Fi."
   - These rogue APs lure users to connect, allowing attackers to hijack connections and steal information.
   - Common tactics include client mis-association, where users connect to a fake AP, and misconfigured APs, where insecure setups allow easy breaches.

2. **Unauthorized Association and Ad-Hoc Connections:**
   - Attackers use soft access points (APs) or ad-hoc connections to gain unauthorized access. This often involves social engineering to get users to click on malicious links that set up these connections.

3. **Honeypot Rogue APs:**
   - Fake access points named after well-known brands or organizations are used to attract users and capture their data for man-in-the-middle attacks and password theft.

4. **AP MAC Address Spoofing:**
   - Attackers sniff the MAC addresses of legitimate APs and spoof their own APs with the same MAC address and SSID.
   - By boosting their signal and sending disassociation signals, attackers force devices to connect to their rogue AP, allowing them to intercept traffic.

5. **KRACK Attack:**
   - The KRACK (Key Reinstallation Attack) exploits a flaw in WPA2 by reusing cryptographic nonces during the four-way handshake, compromising data security and allowing attackers to steal sensitive information.
   - This attack has been largely patched but was a significant threat when first discovered.

6. **Signal Jamming:**
   - Jamming involves overwhelming the wireless channel with noise to disrupt communication.
   - It's important to use jammers responsibly and legally, as improper use can interfere with emergency services and other critical communications.

7. **Cracking WPA/WEP Keys:**
   - Tools like aircrack-ng are used to crack WEP and WPA/WPA2 keys by capturing and analyzing wireless traffic.
   - WEP cracking requires capturing a large number of initialization vectors, while WPA cracking involves capturing handshake packets and performing dictionary attacks.
   - It's crucial to use these techniques ethically and legally, typically on your own networks or in controlled environments.

8. **Practical Steps for WPA/WEP Cracking:**
   - Switch the network interface to monitor mode and capture traffic.
   - Perform deauthentication attacks to force clients to reconnect and capture handshake packets.
   - Use tools like aircrack-ng to analyze the captured data and crack the encryption keys.