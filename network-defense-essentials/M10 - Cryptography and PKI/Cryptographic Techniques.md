- **Definition and History:**
  - Cryptography involves encoding messages so that only intended recipients can read them.
  - Historically used to protect sensitive communications, from ancient times through World War II at Bletchley Park, where cryptography and computation advanced significantly.

- **Purpose:**
  - Converts plaintext (readable data) into ciphertext (encrypted data) to protect it during transmission over insecure mediums like the Internet.

### Objectives of Cryptography

- **Confidentiality:**
  - Ensures that only authorized entities can access the data.

- **Authentication:**
  - Verifies the identity of the sender or receiver.

- **Integrity:**
  - Confirms that the message has not been altered during transit.

- **Non-repudiation:**
  - Prevents denial of having sent the message, ensuring accountability.

### Types of Encryption

#### Symmetric Encryption

- **Definition:**
  - Uses the same key for both encryption and decryption.

- **Process:**
  - A message is encrypted using a key, and the same key is used to decrypt the message.

- **Challenges:**
  - Secure key exchange is required to ensure that only authorized parties have the key. Protocols like Diffie-Hellman facilitate secure key exchange.

- **Usage:**
  - Commonly used for encrypting large amounts of data, such as files downloaded from the Internet.

- **Key Points:**
  - Single key used for both encryption and decryption.
  - Both parties must have access to the same key.

#### Asymmetric Encryption

- **Definition:**
  - Utilizes a pair of keys: a public key for encryption and a private key for decryption.

- **Process:**
  - The sender encrypts the message using the recipient's public key. The recipient decrypts it using their private key.

- **Advantages:**
  - Public key can be shared openly, while the private key remains confidential.
  - More suitable for smaller data sizes due to processing overhead.

- **Key Points:**
  - Public key encrypts data; private key decrypts it.
  - Provides secure communication without needing to share keys beforehand.

### Government Access to Keys

- **Definition:**
  - Some countries require organizations to provide copies of encryption keys to the government for potential access under legal circumstances.

- **U.S. Context:**
  - No mandatory Government Access to Keys (GAK). Government requests for access, such as Apple's case, involve specific legal processes and constraints.

### Conclusion

- **Importance:**
  - Cryptography plays a critical role in securing communications and data across the Internet.
  - Understanding both symmetric and asymmetric encryption is crucial for implementing effective security measures.

## Exam
Which of the following objectives of cryptography guarantees that the sender of a message cannot later deny having sent the message and that the recipient cannot deny having received the message?

**Nonrepudiation**: Guarantee that the sender of a message cannot later deny having sent the message and that the recipient cannot deny having received the message.

### 2.

Question 2

Bob had sent an email to John’s email address by attaching a confidential project file to the mail. Before sending the project file, Bob created a digital signature, encrypted the digital signature with a strong key, and attached the signature to the file to prevent improper and unauthorized changes.

Which of the following objectives of cryptography was achieved in the above scenario?

**Integrity**: Trustworthiness of data or resources in terms of preventing improper and unauthorized changes.
