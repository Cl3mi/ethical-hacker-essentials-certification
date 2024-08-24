## Summary of Types of Authentication

### Overview
- **Authentication Types**: Methods used to verify the identity of an entity.
  - **Common Types**: Passwords, smart cards, biometrics.
  - **Factors of Authentication**: Something you know, something you have, something you are.

### Password Authentication
- **Definition**: Traditional method where users enter a memorized password.
- **Security Tip**: Avoid writing passwords on sticky notes; keep them secure.

### Smart Card Authentication
- **Definition**: Uses a physical smart card inserted into a reader connected to a computer.
  - **Function**: Provides cryptographic authentication.

### Biometric Authentication
- **Definition**: Uses physical characteristics for verification.
  - **Types**:
    - **Fingerprint**: Uses the unique patterns of a person's fingerprint.
    - **Retina Scan**: Scans the pattern of blood vessels at the back of the eye.
    - **Iris Scan**: Scans the unique pattern in the colored part of the eye.
    - **Voice Recognition**: Identifies individuals based on voice characteristics.
    - **Other Biometrics**: Includes vein patterns, typing rhythm, and gait.
  - **Differences**:
    - **Retina vs. Iris**:
      - **Retina**: Pattern of blood vessels at the back of the eye.
      - **Iris**: Colored ring around the pupil.
  - **Note**: Biometrics can be spoofed or tricked; awareness of potential for system defeat is crucial.

### Two-Factor Authentication (2FA)
- **Definition**: Combines two different factors of authentication to enhance security.
  - **Factors**:
    - **Something You Know**: Password or PIN.
    - **Something You Have**: Smart card or OTP (One-Time Password).
    - **Something You Are**: Biometrics (e.g., fingerprint).
  - **Common Combinations**:
    - Password and smart card.
    - Password and biometrics.
    - Smart card and biometrics.
  - **Advantages**: Provides additional security compared to single-factor authentication.

### Multi-Factor Authentication (MFA)
- **Definition**: Uses three or more authentication factors.
  - **Example**: Combining password, smart card, and biometrics for enhanced security.

### Single Sign-On (SSO)
- **Definition**: Allows users to access multiple resources with a single login session.
  - **Advantages**:
    - **Convenience**: Reduces the need to remember multiple passwords.
    - **Efficiency**: Speeds up access and reduces network traffic.
    - **Application**: Works across various systems and resources, such as applications, email, and databases.

### Summary
- **Authentication Methods**: Include passwords, smart cards, biometrics, and combinations thereof.
- **Two-Factor and Multi-Factor Authentication**: Enhance security by using multiple verification methods.
- **Single Sign-On**: Simplifies user access to multiple resources with one set of credentials.

### Centralized Authorization

- **Definition**: A single, centralized database controls access to all resources.
- **Example**: Active Directory.
- **Advantages**:
    - **Simplicity**: Easier to manage access from one central point.
    - **Cost**: Generally cost-effective for managing access.
- **Limitations**:
    - **Applicability**: Not always suitable for all types of applications.

### Decentralized Authorization

- **Definition**: Each network resource has its own separate database for authorization.
- **Challenges**:
    - **Single Sign-On (SSO)**: Fails in decentralized systems because users need to authenticate separately for each resource.
    - **Multiple Credentials**: Users must remember and manage different usernames and passwords for each resource.

### Implicit Authorization

- **Definition**: Access to a secondary resource is granted based on permissions associated with a primary resource.
- **Example**: If you have access to a primary system, you may automatically gain access to certain related secondary resources.
- **Mechanism**: This is based on pre-existing arrangements or permissions.

### Explicit Authorization

- **Definition**: Requires a separate, specific request for access to a resource.
- **Process**:
    - **Authorization Request**: A request is made, usually to a system or network administrator.
    - **Fulfillment**: Access is granted after the request is reviewed and approved.
- **Characteristics**: Not automatic; requires manual intervention to grant access.

### Summary

- **Authorization Systems**:
    - **Centralized**: Single point of control.
    - **Decentralized**: Individual control for each resource.
    - **Implicit**: Access based on permissions from primary resources.
    - **Explicit**: Requires formal requests and approvals for access.