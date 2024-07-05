
- **Authentication and SAM**: 
  - SAM stands for Security Account Manager database.
  - On standalone systems, SAM stores hashed passwords using NTLM authentication.
  - Passwords stored in SAM are vulnerable to cracking.
  
- **Active Directory Security**:
  - In Active Directory environments, passwords are not stored in clear text but are hashed.
  - However, these hashes can still be cracked, albeit with some effort.
  - NTLM authentication used in non-domain systems produces hashes susceptible to cracking.
  
- **Recommendations for Security**:
  - Integrate workstations into an Active Directory domain for enhanced security.
  - Active Directory uses Kerberos authentication by default, which is stronger than NTLM.
  - Small businesses should consider deploying Windows Server and setting up an Active Directory domain.
  - Centralizing authentication through Active Directory reduces vulnerabilities associated with SAM on standalone systems.

These points underscore the importance of using Active Directory for centralized authentication and the vulnerabilities associated with SAM and NTLM authentication in standalone systems.