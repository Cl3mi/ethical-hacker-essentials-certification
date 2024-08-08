- **TTPs Overview:**
  - **TTPs:** Tactics, Techniques, and Procedures.
  - **Analogy:** Like recognizing a person's handwriting style to identify them.

- **Definitions:**
  - **Tactics:** The way the attack is performed from beginning to end.
  - **Techniques:** The technical methods and tools used.
  - **Procedures:** The organizational approach to launching the attack.

- **Purpose:**
  - Identifying patterns and behaviors of threat actors to attribute attacks.

- **Example Scenario:**
  - **Office Environment:** Fourth floor with customer support employees who only use one app.
  - **Expected Behavior:** Logging off the app during breaks, no use of browsers, downloads, or command line tools.

- **Anomalous Behavior:**
  - **Indicators of Compromise:**
    - Scanning the network.
    - Using PowerShell or command line tools.
    - Sending data to a proxy server or command and control server.
    - HTTP user agents accessing other resources.
    - DNS tunneling or Web Shell activity.

- **Key Takeaway:**
  - Unusual behaviors in a predictable environment can indicate adversary activity, and identifying these can help detect and mitigate attacks.