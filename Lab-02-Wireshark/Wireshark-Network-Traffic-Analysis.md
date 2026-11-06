# Lab 02: Wireshark Network Traffic Analysis

## 1. Objective

The objective of this lab was to capture and analyze network traffic using Wireshark and understand DNS, TCP, and UDP protocols.

## 2. Tools Used

- Wireshark
- Windows Operating System
- Google Chrome

## 3. Practical Activities

### Task 1: Network Traffic Capture

Started a network capture in Wireshark and generated network traffic by opening websites in Google Chrome.

### Task 2: Packet List Analysis

Observed captured packets and studied the following fields:

- Source IP
- Destination IP
- Protocol
- Length
- Info

### Task 3: DNS Investigation

Applied the DNS display filter:

`dns`

Identified a DNS query for:

- Domain Name: microsoft.com
- Query Type: Standard Query
- Response Type: Standard Query Response
- Resolved IP Address: 72.145.35.97

This demonstrated how DNS translates domain names into IP addresses.

### Task 4: TCP Investigation

Applied the TCP display filter:

`tcp`

Selected TCP packets and examined Transmission Control Protocol details.

Observed TCP flags in the selected packets:

- SYN: Not Set 
- FIN: Not Set 
- ACK: Set 

TCP flags help analysts understand connection-related communication.

### Task 5: UDP Investigation

Applied the UDP display filter:

`udp`

Observed DNS and mDNS traffic and explored the User Datagram Protocol section.

- Source Port: [61647]
- Destination Port: [53<img width="720" height="1280" alt="WhatsApp Image 2026-11-06 at 2 25 46 PM" src="https://github.com/user-attachments/assets/b04cd152-68fb-482c-88cb-b86e6f99ba99" />
]

UDP is a connectionless transport protocol commonly used by DNS and other network services.

## 4. Key Learning Outcomes

Through this practical lab, I learned:

1. How to capture network packets using Wireshark.
2. How to apply DNS, TCP, and UDP display filters.
3. How to identify DNS queries and responses.
4. How to identify resolved IP addresses.
5. How to inspect TCP flags.
6. How to examine UDP packet details and ports.
7. How network traffic analysis supports SOC operations.

## 5. Conclusion

This practical exercise improved my understanding of network traffic analysis and common network protocols.

Wireshark can help SOC Analysts investigate network communication, identify unusual activity, and collect evidence for further investigation.

**Lab Status:** Practical investigation in progress.
