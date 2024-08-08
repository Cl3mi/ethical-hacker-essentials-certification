- **Understand Developer Practices**:
  - Ask developers about their assumptions regarding data size and type.
  - Ensure they test data inputs and enforce appropriate limits to prevent buffer overruns.

- **Learn About Databases**:
  - Familiarize yourself with databases through classes or tutorials (e.g., MySQL tutorials).
  - Understand different variable types (e.g., strings, floating points) and how they are handled.

- **Check Input Handling**:
  - Verify that developers are rejecting queries containing potentially harmful content.
  - Avoid building Transact-SQL statements directly from user input.

- **Implement Validation**:
  - Use pre-built SQL statements and enforce multiple layers of validation in your application and SQL Server.

- **Use Security Tools**:
  - Employ tools like DSS (injection vulnerability scanner) to identify potential vulnerabilities in your database.
  - Use Burp Suite to test web applications and their SQL vulnerabilities.
  - Utilize HCL AppScan to assess vulnerabilities in web applications and underlying databases.

- **Proactive Testing**:
  - Regularly test your database, web applications, and web servers for vulnerabilities to prevent attacks by external threat actors.

- **Practical Experience**:
  - Engage in practical exercises and labs to become familiar with attack methodologies, terminologies, and tools.

- **Upcoming Topics**:
  - The next module will cover wireless attacks and countermeasures.

## Quiz answers returned this:
### 1. Question:
Some countermeasures to defend against SQL injection attacks are listed below:
- Reject entries that contain binary data, escape sequences, and comment characters
- Never build Transact-SQL statements directly from user input and use stored procedures to validate user input
- Implement multiple layers of validation and never concatenate user input that is not validated
- Avoid constructing dynamic SQL with concatenated input values
- **Design the code such that it traps and handles exceptions appropriately**
- Apply least privilege rules to run the applications that access the DBMS
- Validate user-supplied data as well as data obtained from untrusted sources on the server side
- Avoid quoted/delimited identifiers as they significantly complicate all whitelisting, black-listing, and escaping efforts
- Use a prepared statement to create a parameterized query to block the execution of the query
- Ensure that all user inputs are sanitized before using them in dynamic SQL statements
- Use regular expressions and stored procedures to detect potentially harmful code.

### 2. Question:
- Make no assumptions about the size, type, or content of the data that is received by your application
- Test the size and data type of the input and enforce appropriate limits to prevent buffer overruns
- **Test the content of string variables and accept only expected values**
- Reject entries that contain binary data, escape sequences, and comment characters
- Never build Transact-SQL statements directly from user input and use stored procedures to validate user input
- Implement multiple layers of validation and never concatenate user input that is not validated
- Avoid constructing dynamic SQL with concatenated input values