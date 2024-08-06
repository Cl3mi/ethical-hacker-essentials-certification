1. **Side-Channel Attacks**:
   - **Definition**: Indirect attacks targeting the hardware or environment rather than the service itself.
   - **Examples**:
     - **Cross-Guest VM Breach**: Attacker on the same physical host as the target uses techniques to access information from processor cache or other side channels.
     - **Timing Attacks**: Exploit variations in processing time.
     - **Data Remanence Attacks**: Extract leftover data from storage.
     - **Acoustic Cryptanalysis**: Analyzes server's acoustic vibrations to infer data.
     - **Power Monitoring Attacks**: Observes power usage patterns during cryptographic operations.
     - **Differential Fault Analysis**: Creates and analyzes faults to glean information.

2. **Cloud Wrapping**:
   - **Definition**: Manipulating SOAP (Simple Object Access Protocol) messages.
   - **Method**: Attacker intercepts and modifies SOAP messages to extract or alter information.

3. **Man-in-the-Cloud Attack**:
   - **Definition**: Similar to man-in-the-middle but targets cloud synchronization.
   - **Method**: Attacker installs malicious code to steal and later restore synchronization tokens, accessing cloud files.

4. **Cloud Hopper Attacks**:
   - **Definition**: Attacks targeting Managed Service Providers (MSPs).
   - **Method**: Attacker uses spear-phishing to compromise MSP staff and gain access to multiple organizations' cloud services.

5. **Cryptojacking Cloud**:
   - **Definition**: Unauthorized use of cloud resources for cryptocurrency mining.
   - **Method**: Embeds crypto mining scripts into cloud services or compromised websites to mine cryptocurrency using the victim's resources.

6. **Cloudborne Attacks**:
   - **Definition**: Attacks targeting the hardware (bare metal) of cloud servers.
   - **Method**: Attacker injects backdoors into server firmware to exfiltrate data and bypass security.

7. **Cloud Attack Tools**:
   - **Lazys3**: A tool for brute-forcing Amazon S3 buckets to find vulnerabilities.
   - **Nimbus Stratus**: A tool for fingerprinting and exploiting Amazon cloud architectures, extracting credentials and metadata.
   - **Other Tools**:
     - **S3 Scanner**
     - **CC Cat**: For cloud container attacks
     - **PACU**
     - **Dumpster Diver**