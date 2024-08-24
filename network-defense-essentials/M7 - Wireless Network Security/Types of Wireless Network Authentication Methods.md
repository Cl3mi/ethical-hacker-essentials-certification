### Authentication Methods

1. **Open System Authentication**
   - **Description:**
     - Allows any device with a wireless NIC to communicate.
     - **Handshake Process:**
       - During the handshake between the wireless client and access point, no security negotiation occurs.
       - The access point does not enforce any security measures.
       - Data is transmitted in the open, which means it is unencrypted and vulnerable.
   - **Considerations:**
     - **Avoidance:**
       - Open system authentication is not recommended due to its lack of security. It permits unauthorized access to the network.

2. **Shared Key Authentication**
   - **Description:**
     - Involves a pre-shared key (PSK) used for authentication.
     - **Process:**
       - The access point and client store a hashed form of the pre-shared key.
       - When the client attempts to connect, it exchanges hashes with the access point.
       - If the hashes match, access is granted to the network.
       - **Example Scenario:**
         - Asking a friend for the Wi-Fi password at their home.
         - The password is essentially the pre-shared key used in the authentication process.
   - **Considerations:**
     - **Security:**
       - More secure than open system authentication but may still have vulnerabilities, particularly if the key is weak or compromised.

3. **802.1X Authentication (EAP/RADIUS)**
   - **Description:**
     - Uses a RADIUS server for authentication.
     - **Process:**
       - The client authenticates with the wireless access point.
       - The access point forwards authentication requests to the RADIUS server.
       - The RADIUS server checks the provided credentials (username and password).
       - If authentication is successful, the RADIUS server sends back a confirmation to the access point.
       - **Session Keys:**
         - Uses a multicast group key and per-station unicast session key to encrypt communication.
   - **Considerations:**
     - **Security:**
       - Provides a more secure authentication mechanism compared to shared key authentication.
       - Suitable for enterprise environments where centralized management of credentials is needed.

### Summary

- **Open System Authentication:** Lacks security and is not recommended due to its open nature.
- **Shared Key Authentication:** Uses a pre-shared key for authentication, more secure than open system but potentially vulnerable.
- **802.1X Authentication (EAP/RADIUS):** Utilizes a RADIUS server for robust authentication and encryption, suitable for enterprise use.

## Exam
- **Question 1**
    
    **Which of the following types of authentication uses a null authentication algorithm that does not verify whether it is a user or a machine requesting network access and uses cleartext transmission to allow the device to associate with an AP?**
    
    - **Open system authentication process**
        - **Explanation:** Open system authentication does not involve any verification of the user or device requesting access. It allows any device to associate with an Access Point (AP) using a null authentication algorithm and cleartext transmission.
- **Question 2**
    
    **In which of the following Wi-Fi authentication methods does each wireless station receive a secret key over a secure channel that is distinct from the 802.11 wireless network communication channels to establish a network connection?**
    
    - **Shared key authentication process**
        - **Explanation:** In the shared key authentication process, wireless stations receive a shared secret key over a secure channel, distinct from the standard wireless communication channels, to establish a network connection.