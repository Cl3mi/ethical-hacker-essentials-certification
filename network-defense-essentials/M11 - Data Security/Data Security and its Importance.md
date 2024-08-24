# Data Security Overview

## Importance of Data Security

- **Business Critical Data**
  - Data is fundamental to organizational operations.
  - Includes accounting files, customer interactions, employee information, benefit details, databases, software, and personal data.
  - Protection is crucial for all types of data, including that of customers and employees.

- **Ransomware Threat**
  - Attackers lock files with encryption and demand payment to prevent data release.
  - Personal and business data is targeted to extort payments and cause reputational damage.

## Risks in Business Environments

- **Data Loss Risks**
  - **Stolen Devices**: Loss of data on laptops or mobile devices.
  - **Unauthorized Transfer**: Employees transferring data using unauthorized methods.
  - **Improper Categorization**: Sensitive data misclassified as less critical.
  - **Data Theft**: Theft by employees or third parties.

- **Types of Data at Risk**
  - **Personally Identifiable Information (PII)**: Social security numbers, credit card information, health and employment details.
  - **Corporate Data**: Sales data, R&D data, financial transactions.
  - **Impacts of Data Loss**:
    - Brand and reputation damage.
    - Loss of customers and market share.
    - Potential fines, penalties, and lawsuits.

## Types of Data to Monitor

- **Data at Rest**
  - Stored in physical locations such as hard drives, SSDs, flash drives, or CDs.
  - Protection Methods:
    - **Encryption**: Ensures data cannot be accessed without authorization.
    - **Password Protection**: Restricts access to authorized users.
    - **Tokenization**: Uses tokens to secure data access.
    - **Data Federation**: Distributes control across multiple locations.

- **Data in Use**
  - Data actively being used or processed, typically stored in RAM.
  - Protection Methods:
    - **Authentication**: Ensures only authorized users can access data.
    - **Memory Encryption**: Encrypts data in RAM.
    - **Strong Identity Management**: Maintains control over user access and data handling.

- **Data in Transit**
  - Data moving between locations via wired or wireless communication.
  - Protection Methods:
    - **Encryption**: Uses SSL/TLS for secure communication.
    - **Email Protection**: Uses PGP or S/MIME for secure email transmission.
    - **Firewall Controls**: Helps protect data during transfer.

## Examples of Data Security in Action

- **Data at Rest**: Bank balances in databases secured with encryption and password protection.
- **Data in Use**: Data displayed on a computer screen, protected through strong authentication methods.
- **Data in Transit**: An email being sent securely through various network components, protected by encryption and firewall controls.

## Exam
### Question 1

**In which of the following states of data is it stored or processed by RAM, CPUs, or databases and is not passively stored on the system, but actively moves across IT infrastructure?**

- **Data in use**  
  This refers to data that is actively being processed or accessed by RAM, CPUs, or databases, rather than data that is passively stored or moving across the network.

### Question 2

**Which of the following types of security controls can be used to protect the data at rest?**

- **Tokenization**  
  Tokenization is a method used to protect data at rest by substituting sensitive data with unique identification symbols (tokens) that retain all the essential information about the data without compromising its security.
  