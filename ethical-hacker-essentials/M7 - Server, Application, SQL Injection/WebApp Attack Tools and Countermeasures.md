**Tools for Web Application Attacking**

1. **Burp Suite**
   - Comprehensive tool for web application security testing.
   - Allows for mapping, analyzing, and attacking the web application's surface.
   - Recommended for learning and mastering web application security.

2. **OWASP ZAP (Zed Attack Proxy)**
   - Tool for finding security vulnerabilities in web applications.
   - Useful for discovering and exploiting web app weaknesses.

3. **Metasploit**
   - A versatile tool for various hacking and security testing tasks.
   - Known for its extensive range of exploits and capabilities.

4. **Nikto**
   - Performs initial scans to identify potentially vulnerable pages.
   - Often used in conjunction with other tools for detailed exploitation.

5. **Additional Tools**
   - **Sniper** and **Whisp**: Assist with specific web application attacks.

**Countermeasures to Web Application Attacks**

1. **SQL Injection Prevention**
   - Limit the length of user input.
   - Use custom error messages to avoid revealing sensitive information.

2. **Input Validation and Sanitization**
   - Validate and escape dangerous characters.
   - Employ language-specific libraries and domain validation.
   - Restrict data returned to users.

3. **Broken Session Management**
   - Ensure secure handling of session identifiers and credentials.

4. **Sensitive Data Exposure**
   - Store credentials in hashed form.
   - Generate cryptographic keys securely.

5. **XML External Entity (XXE) Attacks**
   - Configure XML unmarshaling securely.

6. **Broken Access Control**
   - Implement proper roles and permissions.

7. **Security Mechanisms**
   - Disable unused services.
   - Use SSL/TLS to secure communication.
   - Validate headers and cookies.
   - Implement Web Application Firewalls (WAFs) to block malicious scripts.

8. **Cross-Site Scripting (XSS)**
   - Convert non-alphanumeric characters to HTML character entities before displaying user input.

9. **Insecure Deserialization**
   - Check trust boundaries and re-architect if necessary.
   - Regularly patch and check for vulnerabilities.

10. **Monitoring and Logging**
    - Use Security Information and Event Management (SIEM) systems to export and analyze logs.
    - Regularly test and scan web applications for vulnerabilities.

**Tools for Testing and Security Scanning**
- **Stalker**: Web application security scanner.
- **Acunetix**: Automated web vulnerability scanner.
- **MetaSploit**: Comprehensive tool for various hacking tasks.