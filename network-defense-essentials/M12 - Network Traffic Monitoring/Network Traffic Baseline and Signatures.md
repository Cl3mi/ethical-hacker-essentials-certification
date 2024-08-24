## Understanding Traffic Signatures

- **Definition of a Signature**:
  - A signature in network security refers to a set of characteristics used to identify traffic patterns.
  - These characteristics include:
    - Source and destination IP addresses
    - Ports
    - TCP (Transmission Control Protocol) flags (6 different flags)
    - Packet length
    - Time to live (TTL)
    - Round-trip time (RTT)
  - **Purpose**: To characterize and differentiate between normal and suspicious traffic.

- **Application of Signatures**:
  - **Normal Traffic**: Characterized by known, accepted patterns and is allowed to pass through.
  - **Attack Signature**: Identified by deviations from normal patterns and is blocked from entering the network.

## Baseline Normal Traffic Signatures

- **Concept of Baseline**:
  - **Definition**: Establishing a baseline involves identifying what constitutes normal traffic in the network.
  - **Analogies**:
    - **Music**: Similar to recording baseline audio levels before a concert.
    - **Network**: Establishing normal traffic patterns helps to identify abnormal behavior.

- **Steps to Establish Baseline**:
  - **Analyze TCP Traffic**:
    - Look at TCP handshake (SYN, FIN flags).
    - Observe the normal flow of traffic.
  - **Examine Trusted Traffic**:
    - Review how traffic flows within trusted zones, such as a DMZ (demilitarized zone).
  - **Detect Policy Violations**:
    - Identify traffic that deviates from established policies (e.g., disallowed protocols or ports like FTP on ports 20 or 21).

- **Purpose of Baseline**:
  - **Identify Abnormal Traffic**:
    - Any traffic that deviates from the established baseline is scrutinized for potential malicious activity.
  - **Policy Enforcement**:
    - Ensure that all traffic adheres to the defined network policies and rules.

## Exam
### 1. Question 1

**A signature is a set of characters that define network activity, including IP addresses, Transmission Control Protocol (TCP) flags, and port numbers.**    
1 / 1 point

- **True**
- False

**Correct**

A signature is a set of characteristics that define network activity, including IP addresses, Transmission Control Protocol (TCP) flags, and port numbers. It includes a set of rules used to detect malicious traffic entering a network.

### 2. Question 2

**Normal traffic signatures contain acceptable traffic patterns and can be allowed to enter the network.**    
1 / 1 point

- False
- **True**

**Correct**

Signatures are classified into two main categories depending on their behavior:

- **Normal Traffic Signatures**: These represent the normal network traffic within an organization and are defined based on a normal traffic baseline. These signatures do not contain any malicious patterns and can be allowed to enter the network.
  
- **Attack Signatures**: These traffic patterns appear suspicious and are treated as attack signatures. They should not be allowed to enter the network as they often indicate a potential security breach. These signatures deviate from normal traffic patterns and should be carefully analyzed.