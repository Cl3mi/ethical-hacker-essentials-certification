**SQL Injection Overview**

- **SQL (Structured Query Language)**
  - Language used by Relational Database Management Systems (RDBMS) for data operations.

- **What is SQL Injection?**
  - Attack where malicious SQL queries are inputted to manipulate the database.
  - Common attacks: 
    - Create new accounts
    - Delete tables
    - Change passwords
    - Modify prices
  - Risks: Unauthorized access, data compromise, remote code execution.

- **Susceptible Databases**
  - All relational databases (e.g., Microsoft SQL Server, Oracle, IBM Db2, MySQL, PostgreSQL).
  - Some NoSQL databases (e.g., MongoDB) are also vulnerable.

- **Types of SQL Injection Attacks:**
  - **In-Band SQL Injection**: Uses the same communication channel for attack and result retrieval.
    - **Error-Based**: Triggers errors to gain information.
    - **Union-Based**: Uses the UNION keyword to combine results of multiple queries.
    - **Tautology-Based**: Uses always-true conditions (e.g., `1=1`) to bypass authentication.
    - **Stored Procedure-Based**: Exploits stored procedures in the database.
    - **Piggybacked Queries**: Adds additional queries (e.g., `DROP TABLE`) after the original query.
  - **Blind SQL Injection**: No direct error or result feedback.
    - **Boolean-Based**: Uses true/false statements to infer information based on response differences.
    - **Time-Based**: Measures response times to infer data (e.g., `WAITFOR DELAY`).
  - **Out-of-Band SQL Injection**: Uses different channels for attack and result retrieval.
    - **DNS-Based**: Uses DNS requests to exfiltrate data.
    - **HTTP-Based**: Uses HTTP requests to retrieve data.

- **Examples of SQL Injection Methods:**
  - **Tautology-Based Injection**: Manipulates queries to always return true (e.g., `1=1`).
  - **Error-Based Injection**: Induces database errors to gather information about the database.
  - **Union Injection**: Combines malicious queries with legitimate ones using the UNION keyword.
  - **Stored Procedures**: Executes existing database procedures to perform unauthorized actions.
  - **Piggybacked Queries**: Appends malicious queries to legitimate ones (e.g., `DROP TABLE`).
  - **Blind SQL Injection**: Uses indirect methods to infer data from the database.

- **Blind SQL Injection Techniques:**
  - **Boolean-Based**: Evaluates conditions to infer data (e.g., checking if a username starts with a specific letter).
  - **Time-Based**: Uses delays to determine data existence (e.g., `WAITFOR DELAY`).

- **Out-of-Band SQL Injection Techniques:**
  - **DNS-Based**: Exploits DNS requests to retrieve data from the database.
  - **HTTP-Based**: Uses HTTP requests to exfiltrate data.
