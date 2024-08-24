### **1. Monitor CVEs (Common Vulnerabilities and Exposures)**

- **Definition**: CVEs are publicly disclosed cybersecurity vulnerabilities and exposures.
- **Action**: 
  - Regularly check for new vulnerabilities and exploits affecting your containers and orchestration tools.
  - Use websites and databases that list CVEs, such as the Google Hacking Database.

### **2. Use Security Tools**

- **Monitoring**: Employ tools to monitor:
  - Network traffic
  - Container interfaces
  - Overall architecture

### **3. Configure Applications with Normal User Privileges**

- **Principle**: Applications should not run with elevated privileges or as root.
- **Reason**: Running with normal user privileges minimizes potential damage from security breaches.

### **4. Set Host Root File System to Read-Only Mode**

- **Purpose**: Prevent unauthorized changes to the file system.
- **Implementation**: Configure the host's root file system to be read-only, restricting write access.

### **5. Use Application Security Scanning Tools**

- **Scanning**: Regularly scan containers for:
  - Malware
  - Misconfigurations
  - Vulnerabilities

### **6. Best Practices for Docker Security**

- **Avoid Exposing Docker Daemon Socket**:
  - **What**: The socket is an IP address and port for Docker services.
  - **Why**: Exposure can lead to security risks.

- **Use Trusted Images**:
  - **Action**: Ensure all Docker images are from trusted sources.

- **Regularly Patch Host Operating System**:
  - **Action**: Keep the host OS and Docker updated with the latest security patches.

- **Limit Container Capabilities**:
  - **Action**: Only grant containers access to necessary features.

- **Employ Linux Security Modules**:
  - **Modules**: Use seccomp, AppArmor, and SELinux for fine-grained process control.

- **Enable Read-Only Mode**:
  - **File Systems and Volumes**: Set read-only flags to restrict modification.

### **7. Kubernetes Security Practices**

- **Validate File Contents and Paths**:
  - **Action**: Ensure proper validation during all processing stages.

- **Configuration Method for Credential Paths**:
  - **Action**: Handle credential paths securely and raise errors explicitly if needed.

- **Use Well-Tested JSON Libraries**:
  - **Purpose**: Avoid vulnerabilities in JSON parsing and object construction.

- **Validate Composite Components**:
  - **Action**: Ensure proper validation for all components used in configurations.

### **8. Tools for Docker and Host Security**

- **Recommended Tools**:
  - **Twistlock**: Security for containerized environments.
  - **Aqua**: Container security platform.
  - **New Vector**: Container security and compliance.
  - **Cloud Passage Halo**: Broad security solutions for various purposes.
  - **Docker Bench**: Tool to check Docker configuration and security compliance.

- **Action**: Regularly use these tools to identify and rectify security issues.
## Exam
### Question 1

**Which of the following practices should be followed by a cloud administrator to secure the container environment?**  

- Use shared database for each application  
- Always use third-party software  
- Configure the host's root file system in write mode  
- Ensure the authenticated access to registries  
  **Correct**

**Best Practices for Container Security**

- **Configure the host's root file system in read-only mode** to restrict write access and prevent malware injection attacks.
- **Avoid using third-party software** and employ application security scanning tools to protect containers from malicious software.
- **Perform regular scanning** of the images in the repository to identify vulnerabilities or misconfigurations.
- **Deploy application firewalls** to enhance container security and prevent threats from entering the environment.
- **Ensure authenticated access to registries**, including sensitive images and data.
- **Use a separate database for each application** for greater visibility of individual applications and enhanced data management.

---

### Question 2

**Which of the following practices should be followed by a cloud administrator to secure the Docker environment?**  

- Always run Docker daemon using the 'debug' log level  
- Avoid using Linux security modules to gain fine-grained control over the processes  
- Always expose the Docker daemon socket  
- Enable read-only mode on file systems and volumes by setting --read-only flag  
  **Correct**

**Best Practices for Securing Docker Environment**

- **Avoid exposing the Docker daemon socket** because it is a basic entry point for the Docker API.
- **Only use trusted Docker images** as images created by malicious users may contain backdoors.
- **Regularly patch host OS and Docker** with the latest security updates.
- **Limit capabilities** by allowing access only to the features required by the container.
- **Use Linux security modules**, such as seccomp, AppArmor, and SELinux, to gain fine-grained control over processes.
- **Limit resources** such as memory, CPU, maximum number of file descriptors, maximum number of processes, and restarts to prevent DoS attacks.
- **Enable read-only mode on filesystems and volumes** by setting the `--read-only` flag.
- **Set the Docker daemon log level to 'info'** and avoid running Docker daemon using the 'debug' log level.
- **Configure the container application to run as an unprivileged user** to prevent privilege escalation attacks.
- **Install only necessary packages** to reduce the attack surface.
