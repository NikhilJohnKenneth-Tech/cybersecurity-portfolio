# Day 1 – OSI Model

## What is the OSI Model?
The OSI (Open Systems Interconnection) Model is a conceptual framework used to understand how data is transmitted across a network. It divides the communication process into 7 layers, each with a specific function.

It helps in:
- Understanding network communication
- Troubleshooting network issues
- Identifying where security threats occur

---

## OSI Layers Overview

1. Physical Layer  
2. Data Link Layer  
3. Network Layer  
4. Transport Layer  
5. Session Layer  
6. Presentation Layer  
7. Application Layer  

Data flows from Layer 7 → Layer 1 while sending, and Layer 1 → Layer 7 while receiving.

---

## Layer-wise Understanding

### 7. Application Layer
- Closest to the user
- Provides network services like web browsing

**Protocols:** HTTP, HTTPS, FTP, DNS  
**Example:** Opening a website  

---

### 6. Presentation Layer
- Formats data
- Handles encryption and decryption

**Example:** HTTPS encryption (SSL/TLS)

---

### 5. Session Layer
- Manages sessions between devices
- Starts and ends communication

**Example:** Staying logged into a website  

---

### 4. Transport Layer
- Ensures reliable data delivery
- Breaks data into segments

**Protocols:** TCP (reliable), UDP (fast)  
**Example:** File download (TCP), video streaming (UDP)

---

### 3. Network Layer
- Handles IP addressing and routing
- Determines the best path for data

**Protocol:** IP  
**Example:** Sending data from one country to another  

---

### 2. Data Link Layer
- Handles communication within the same network
- Uses MAC addresses

**Example:** Communication within Wi-Fi network  

---

### 1. Physical Layer
- Transmits raw bits over hardware
- Includes cables, signals, and devices

**Example:** Ethernet cable, Wi-Fi signals  

---

## Encapsulation

As data moves through the OSI layers, each layer adds its own header:

- Transport Layer → Adds TCP/UDP header → Segment  
- Network Layer → Adds IP header → Packet  
- Data Link Layer → Adds frame header → Frame  
- Physical Layer → Converts to bits  

This process is called **encapsulation**.

---

## Cybersecurity Perspective

Each layer can be targeted by different types of attacks:

- Application Layer → Phishing, SQL Injection, XSS  
- Transport Layer → Port scanning, SYN flood attacks  
- Network Layer → IP spoofing  
- Data Link Layer → ARP spoofing, Man-in-the-Middle attacks  
- Physical Layer → Hardware tampering  

---

## Professional Understanding

The OSI model is not just theoretical. It helps identify where a network issue or attack occurs.

Instead of memorizing layers, it is used to:
- Troubleshoot problems step-by-step
- Analyze attacks based on layers
- Understand how systems communicate in real-world environments

---

## Key Takeaways

- The OSI model divides networking into 7 layers
- Each layer has a specific responsibility
- It is widely used for troubleshooting and security analysis
- Helps identify where communication fails or where attacks occur
