- **Encryption Necessity:**
  - Wi-Fi networks are open and accessible to any device.
  - Without encryption, data transmitted can be read, recorded, and analyzed.
  
## Evolution of Wireless Network Security

### 802.11i Standard

- **Initial Encryption: WEP (Wired Equivalent Privacy):**
  - WEP was an early encryption protocol for wireless networks.
  - **Issues:**
    - Easily hacked due to weak implementation.

- **Extensible Authentication Protocol (EAP):**
  - EAP provides flexible authentication options.
  - Supports various methods like tokens, Kerberos, smart cards, and biometrics.
  - **Examples:**
    - LEAP (Lightweight EAP) by Cisco for improved authentication.

### WPA (Wi-Fi Protected Access)

- **Improvements Over WEP:**
  - Introduced Temporal Key Integrity Protocol (TKIP).
  - Replaced static keys with temporal keys to enhance security.
  - **Limitations:**
    - Continued use of DES and 3DES.
    - Early versions of TKIP were still vulnerable to attacks.

### WPA2

- **Advancements:**
  - Replaced TKIP with Advanced Encryption Standard (AES) and Counter Mode Cipher Block Chaining Message Authentication Code Protocol (CCMP).
  - **WPA2-Enterprise:**
    - Utilizes external authentication servers like RADIUS.
  - **WPA2-Personal:**
    - Pre-shared keys (PSK) are stored in a hash format, which can be susceptible to attacks.

### WPA3

- **Current Standard:**
  - Uses AES-GCMP (Galois/Counter Mode Protocol) with 256-bit encryption.
  - **WPA3-Personal:**
    - Employs Secure Exchange of Equals (SAE) or Dragonfly Key Exchange.
    - **Benefits:**
      - Resistant to offline dictionary attacks and key recovery attacks.
  - **WPA3-Enterprise:**
    - Provides enhanced security with GCMP-256, HMAC-SHA-384, and Elliptic Curve Digital Signature Algorithm (ECDSA).
    - **Key Size:**
      - Initialization vector size up to 2^64 (10 sextillion).

## Recommendations for WPA3 Implementation

- **Full WPA3 Adoption:**
  - Ensure all devices and access points are WPA3 compatible.
  - Avoid allowing devices to fall back to WPA2, as this creates vulnerabilities.

## Security Issues with Previous Protocols

- **WEP:**
  - CRC-32 integrity issues, weak initialization vectors, and lack of centralized key management.
- **WPA:**
  - Vulnerable pre-shared keys, lack of forward secrecy, and insecure random number generators.
- **WPA2:**
  - Susceptible to dictionary attacks, exfiltration of hashes, rainbow table attacks, and vulnerabilities like Hole196 and KRACK.
