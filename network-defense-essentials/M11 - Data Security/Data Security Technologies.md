## Key Data Security Technologies

### 1. Access Control
- **Components**: Authentication and Authorization
- **Frameworks**: AAA (Authentication, Authorization, and Accounting), IAM (Identity and Access Management)
- **Purpose**: Ensures only authorized users have access to data and resources.

### 2. Data Encryption
- **Concept**: Ubiquitous encryption
  - **Scope**:
    - **Data in Transit**: Data being sent over networks
    - **Data at Rest**: Data stored on devices or servers
    - **Data in Use**: Data being processed or used
- **Objective**: Protect data by transforming it into a form that cannot be read without proper decryption.

### 3. Data Masking
- **Concept**: Data masking obscures sensitive information
  - **Comparison**: Similar to document redaction (e.g., black markers used in classified documents)
  - **Implementation**: Replaces sensitive data with random characters or codes
    - **Example**: Social security numbers in a database are shown as Xs or random characters.

### 4. Data Resilience and Backup
- **Concept**: Ensure critical data has backup copies
  - **Purpose**: Protects against data loss from incidents like ransomware attacks
    - **Process**:
      - Attackers encrypt data and demand ransom
      - Backup data is used to restore the original data
      - Encrypted stolen data can be disregarded as it is protected

### 5. Data Destruction
- **Concept**: Properly dispose of unused data
  - **Devices**: Phones, desktops, hard drives, flash drives
  - **Purpose**: Prevents intercepted data from being accessed or used by unauthorized parties

### 6. Data Retention
- **Concept**: Keeping backup data for specific durations
  - **Guidelines**:
    - Based on regulations, corporate policies, and compliance requirements
  - **Purpose**: Ensure data is available for required periods as per legal and operational needs
