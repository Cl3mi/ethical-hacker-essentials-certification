### What is Hashing?

- **Definition**: Hashing is a process that transforms input data (like text or files) into a fixed-size string of characters, typically a hash value or checksum.
- **Purpose**: The primary goal is to produce a unique hash for each unique input, making it easy to verify the integrity of data.

### Hashing Process

- **Input**: You can input various types of data, including text or files.
- **Output**: The result is a unique string of characters, which represents the hash of the input data.

### Key Features of Hashing

- **Uniqueness**: Hashing algorithms generate a unique hash for each unique input. Even a tiny change in the input will produce a completely different hash.
- **Example**: MD5 and SHA-1 are common hashing algorithms used to generate these unique strings.

### Practical Implications

- **File Size**: Hashing can handle files of significant size, up to four gigabytes (4 billion bytes). Each byte consists of 8 bits.
- **Efficiency**: Hashing processes a large amount of data efficiently. Instead of manually checking billions of bits, hashing provides a quick way to verify data integrity.
- **Integrity Check**: A hash will change if even a single bit of the original data changes. This makes it a reliable method for detecting any alterations in the data.

## Exam
Here are the answers to the questions based on the provided information:

### Question 1

**Which of the following algorithms uses a cryptographic key along with a cryptographic hash function to verify the integrity of data and authentication of a message?**

- **HMAC**

**Explanation**: HMAC (Hash-based Message Authentication Code) combines a cryptographic hash function with a secret key to provide both data integrity and authentication.

### Question 2

**Identify the algorithm that uses the sponge construction in which the message blocks are XORed into the initial bits of the state, which the algorithm then invertibly permutes.**

- **SHA-3**

**Explanation**: SHA-3 uses the sponge construction method. In this process, the input message blocks are XORed into the state, which is then permuted through the sponge function to produce the hash output.
