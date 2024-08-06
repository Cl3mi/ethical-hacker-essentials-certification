- **WEP (Wired Equivalent Privacy):**
  - **Initial Standard**: First wireless encryption standard, advertised as providing security equivalent to wired networks.
  - **Flaws**: Hackable due to weak initialization vector (IV) and flawed RC4 protocol implementation.

- **EAP (Extensible Authentication Protocol):**
  - **Introduction**: Introduced to enhance wireless security with various authentication methods.
  - **Associated with**: WPA and its implementation LEAP (Lightweight Extensible Authentication Protocol) by Cisco.

- **WPA (Wi-Fi Protected Access):**
  - **Introduction**: Replaced WEP with improved security.
  - **Key Feature**: Implemented Temporal Key Integrity Protocol (TKIP) to address WEP’s weaknesses by using rotating keys.
  - **Weakness**: TKIP was also eventually found to be hackable.

- **WPA2:**
  - **Introduction**: Improved version of WPA with stronger security features.
  - **Flavors**:
    - **WPA2 Personal**: Used in home and small business networks, authenticates directly at the access point.
    - **WPA2 Enterprise**: Uses external servers (e.g., RADIUS) for authentication, offering enhanced security and integration with directory services (e.g., Active Directory).
  - **Key Features**: 
    - **AES (Advanced Encryption Standard)**: Provides robust encryption.
    - **CCMP (Counter Mode with Cipher Block Chaining Message Authentication Code Protocol)**: Enhances encryption security.

- **WPA3:**
  - **Introduction**: Third-generation Wi-Fi security protocol with improved features.
  - **Key Features**:
    - **GCMP-256**: Provides stronger encryption compared to WPA2.
    - **HMAC-SHA-384**: For enhanced authentication.
    - **SAE (Simultaneous Authentication of Equals)**: A new method for password-based authentication in WPA3 Personal, resistant to dictionary and key recovery attacks.
  - **WPA3 Enterprise**: Includes advanced encryption and cryptographic capabilities like ECDSA-384 (Elliptic Curve Digital Signature Algorithm).
  - **Challenges**: Some attacks target WPA3’s Dragonfly Key Exchange; ensure all devices support WPA3 to avoid fallback to WPA2.

- **Practical Advice**:
  - **WEP**: Avoid due to its inherent vulnerabilities.
  - **WPA2**: Better than WEP, but WPA3 is recommended for future-proofing.
  - **WPA3**: Use if all devices are compatible; prevent downgrading to WPA2 by ensuring all devices support WPA3.
