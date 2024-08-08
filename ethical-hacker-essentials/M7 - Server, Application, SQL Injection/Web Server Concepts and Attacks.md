- **Web Server Attacks Overview**
  - Web servers are essential for hosting web applications and sites.
  - They serve various roles: hosting web apps, static content, and data stores.
  - A web client interacts with the server via HTTP requests.
  - Web servers can run multiple applications and virtual hosts.

- **Components of Web Servers**
  - Includes web server software (e.g., Apache, Nginx, IIS), web containers, and services.
  - Data storage for applications, both static and dynamic.
  - Virtual hosting for managing multiple domains on one server.
  - Folders and files on disks containing configurations, logs, and executables.
  - Use of proxies for security and anonymity.

- **Security Layers and Challenges**
  - **Level 1 (Web Server Security)**
    - Involves firewalls, IDS/IPS systems, and security measures at the web server level.
  - **Level 2 (Network Security)**
    - Concerns routers, switches, VLANs, and routing protocols.
  - **Level 3 (Operating System Security)**
    - Includes securing Windows (Workstations and Servers), Linux (Ubuntu, SELinux), and macOS.
  - **Level 4 (Database Security)**
    - Securing databases like MySQL, Microsoft SQL Server, Oracle, including data masking and encryption.
  - **Level 5 (Application/Service Security)**
    - Focuses on securing web servers (e.g., Apache, Nginx, IIS) against vulnerabilities and attacks.

- **Impact of Web Server Attacks**
  - Accounts can be compromised, websites defaced, and root access gained.
  - Attackers can exploit vulnerabilities to access other parts of the network.
  - Data can be tampered with or stolen, leading to reputational damage for organizations.

- **Reasons for Compromise**
  - Improper file and directory permissions.
  - Configuration errors due to lack of expertise or adherence to security policies.
  - Default accounts or passwords left unchanged.
  - Presence of sample configuration files or scripts that are unnecessary for production.

- **Types of Web Server Attacks**
  - **DNS Server Hijacking**
    - Attackers compromise DNS servers to redirect users to fake websites.
  - **DNS Amplification**
    - Exploits DNS servers to amplify traffic against a target, causing a DDoS attack.
  - **Directory Traversal**
    - Exploits improper input handling to access unauthorized directories and files.
  - **Website Defacement**
    - Attackers modify the appearance of a website to spread messages or disrupt operations.
  - **Weak Configuration**
    - Misconfigurations in remote administration, unnecessary services, or outdated certificates.
  - **HTTP Response Splitting**
    - Manipulates server responses to redirect users to malicious sites.
  - **Web Cache Poisoning**
    - Modifies cache entries to redirect users to fake or malicious content.
  - **SSH Brute Force Attack**
    - Attempts to gain unauthorized access by guessing SSH credentials.
  - **Web Server Password Cracking**
    - Uses brute force or dictionary attacks to crack weak or default passwords.
  - **Server Side Request Forgery (SSRF)**
    - Exploits web server's ability to send requests to other systems on behalf of the user.

- **Tools and Techniques**
  - Use of security tools like THC Hydra for password cracking.
  - Awareness of common vulnerabilities and configurations that lead to attacks.

This comprehensive overview covers the essentials of web server attacks, their impact, and strategies for prevention and mitigation.