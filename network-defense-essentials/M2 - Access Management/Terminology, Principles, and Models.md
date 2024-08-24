### Introduction
- **Access Control Principles and Terminology**: This section covers the foundational concepts and terminology in access control, followed by an exploration of Identity Access Management (IAM).

### Access Control
- **Definition**: Access control is about selective restriction, ensuring that not everyone has access to everything.
- **Example**: Medical records are restricted to specific medical professionals; similarly, access to personal information like cryptocurrency or credit information is restricted to authorized individuals only.

### Key Components
- **Subject**: The entity requesting access (e.g., user, process, or program).
- **Object**: The resource being accessed (e.g., files, printers, applications).
- **Reference Monitor**: Checks access requests against the rules for authentication and authorization.

### Access Control Principles
1. **Separation of Duties (SoD)**
   - Breaks down authorization into several steps.
   - Different privileges are assigned to different steps.
   - Prevents any single individual from having complete control over all steps.

2. **Need-to-Know**
   - Access is granted based on the necessity of the information for the job.
   - Example: A secret clearance allows access only to relevant information, not everything.

3. **Principle of Least Privilege (POLP)**
   - Users are given only the privileges necessary to perform their job functions.
   - Reduces the risk of accidental or malicious misuse of information.

### Access Control Models
1. **Discretionary Access Control (DAC)**
   - Users have control over their resources and can assign access to others.
   - Example: A user in the accounting department can control who accesses their folders.

2. **Mandatory Access Control (MAC)**
   - Access rights are determined by a central authority or system owner.
   - End-users cannot modify access permissions.
   - Typically used in environments requiring high security.

3. **Role-Based Access Control (RBAC)**
   - Access is assigned based on roles within an organization.
   - Users are given access to resources based on their role in the organization.
   - Example: An accounting department group has access to all accounting resources.

4. **Rule-Based Access Control (RB-RBAC)**
   - Access control rules are dynamically applied based on context or conditions.
   - Example: Access permissions may change based on the location or device used for login.

### Practical Implementations
- **User Account Control (UAC)**: Windows feature that manages permissions for system changes.
- **Access Control Lists (ACLs)**: Define user permissions for files and folders.
- **Group Policies**: Define and enforce access control policies across an organization.
- **Just Enough Administration (JEA)**: Provides limited administrative capabilities based on needs.
- **Windows Admin Center (WAC)**: Implements RBAC and provides tools for network administration.

### Summary of Key Points
- **Separation of Duties**: Distributes authority to prevent abuse.
- **Need-to-Know**: Limits access to necessary information only.
- **Least Privilege**: Grants minimal access rights necessary for job functions.
- **DAC, MAC, RBAC, and RB-RBAC**: Different models for managing access based on user roles, system requirements, and dynamic conditions.