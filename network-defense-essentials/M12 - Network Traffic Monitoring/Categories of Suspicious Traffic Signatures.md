#### 1. Informational
- **Definition**: Signatures that might seem suspicious but may not always indicate a real threat.
- **Purpose**: Provide information that could be useful for further analysis.
- **Action**: Monitor these signatures to gather data, but they may not require immediate action unless further validated.

#### 2. Reconnaissance
- **Definition**: Initial phase of an attack where the attacker gathers information about the network.
- **Activities**:
  - Scanning for live systems.
  - Collecting details about network resources and their configurations.
- **Purpose**: To find vulnerabilities and plan an attack.
- **Action**: Set triggers for notifications or blocking actions when reconnaissance activities are detected.

#### 3. Unauthorized Access
- **Definition**: Attempts to access files, folders, or resources without proper authorization.
- **Characteristics**: 
  - An unauthorized account or user trying to access restricted resources.
- **Purpose**: Indicates potential breaches or misuse of resources.
- **Action**: Block access attempts or alert administrators to prevent unauthorized access.

#### 4. Denial-of-Service (DoS)
- **Definition**: Flooding a resource with excessive data to make it unavailable.
- **Characteristics**:
  - Overwhelming a system or service to disrupt its normal functioning.
- **Purpose**: To deny service to legitimate users.
- **Action**: Implement measures to block the attack or alert administrators to mitigate the impact.

## Exam:
### 1. Question 1

**Which of the following categories of traffic signature appear to be suspicious but might not always be malicious?**    
1 / 1 point

- **Informational**    
  Correct

  **Explanation**: Informational traffic signatures might seem suspicious but are not necessarily indicative of a malicious threat. They provide information that needs further analysis to determine if there is an actual threat.

---

### 2. Question 2

**Don, a professional hacker, targeted manager Ethan working for an organization. He launched a brute-force attack on Ethan’s official email account to steal the organization’s confidential data. John, the network administrator, identified suspicious login attempts from an external network and asked Ethan to change the password immediately.**

**Which of the following types of suspicious network traffic signatures John has identified in the above scenario?**    
1 / 1 point

- **Unauthorized access**    
  Correct

  **Explanation**: The suspicious login attempts from an external network indicate an unauthorized access attempt. John identified this type of signature because it involves attempts to gain access to a system or account without proper authorization.