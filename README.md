# Task-5-Capture-and-Analyse-Network-Traffic-Using-Wireshark-
Capture and analyze live network traffic using Wireshark to identify at least three basic protocols. Deliverables include a .pcap file and a short report of identified protocols. This task builds packet analysis and protocol awareness skills.
# Network Traffic Capture and Analysis with Wireshark

## Task 5: Elevate Labs Cyber Security Internship

### Objective
The primary objective of this task was to gain hands-on experience in capturing and analyzing live network traffic using Wireshark. This involved identifying basic network protocols and understanding different traffic types. [cite: 2, 8]

### Tools
* **Wireshark:** A free and open-source packet analyzer used for network troubleshooting, analysis, software and communications protocol development, and education. [cite: 3]

### Deliverables
* A packet capture (`.pcap`) file containing the captured network traffic. [cite: 3]
* A short report summarizing the findings and detailing the identified protocols. [cite: 3]

### Key Concepts Explored
* Packet capture [cite: 11]
* Protocol analysis [cite: 11]
* TCP/IP [cite: 11]
* Network troubleshooting [cite: 11]
* Filtering [cite: 11]

### How I Completed This Task

1.  **Wireshark Installation:** I downloaded and installed Wireshark on my system. [cite: 4]
2.  **Traffic Generation:**
    * I started Wireshark and selected my active network interface for capturing. [cite: 4]
    * To generate traffic, I browsed several websites and performed a ping to a server. [cite: 5]
    * After approximately one minute of generating traffic, I stopped the capture. [cite: 5]
3.  **Packet Analysis and Filtering:**
    * Within Wireshark, I applied filters to inspect different types of packets. [cite: 6]
    * I specifically filtered for common protocols like HTTP, DNS, and TCP to identify their presence and characteristics. [cite: 6]
    * I identified at least three different protocols in the capture. [cite: 6]
4.  **Exporting the Capture:** I exported the captured packets as a `.pcap` file, which is included in this repository. [cite: 7]
5.  **Summarizing Findings:** I created a short report detailing the identified protocols and packet types, which is also included. [cite: 8]

### Identified Protocols (Examples from my capture)

* **TCP (Transmission Control Protocol):** Observed during web Browse for reliable data transfer. I saw SYN, ACK, and FIN packets used for connection establishment and termination.
* **DNS (Domain Name System):** Identified DNS query packets and their corresponding responses when resolving domain names to IP addresses.
* **HTTP (Hypertext Transfer Protocol):** Detected HTTP GET requests and 200 OK responses, indicating successful retrieval of web page content.

### Interview Questions (Self-Reflection)

This task helped me understand concepts relevant to the potential interview questions:

1.  **What is Wireshark used for?**
    Wireshark is used for capturing and analyzing network traffic, troubleshooting network issues, and for network protocol development and education. [cite: 1, 8, 9, 11]
2.  **What is a packet?**
    A packet is a small block of data transmitted over a network.
3.  **How to filter packets in Wireshark?**
    Packets can be filtered in Wireshark using display filters in the filter bar (e.g., `http`, `dns`, `tcp`). [cite: 6, 9]
4.  **What is the difference between TCP and UDP?**
    TCP (Transmission Control Protocol) is a connection-oriented, reliable protocol that guarantees delivery and order of packets. UDP (User Datagram Protocol) is a connectionless, unreliable protocol that prioritizes speed over guaranteed delivery. [cite: 9]
5.  **What is a DNS query packet?**
    A DNS query packet is a request sent by a client to a DNS server to resolve a human-readable domain name into an IP address. [cite: 10]
6.  **How can packet capture help in troubleshooting?**
    Packet capture allows for detailed inspection of network communication, helping to identify bottlenecks, protocol errors, misconfigurations, and security issues. [cite: 11]
7.  **What is a protocol?**
    A protocol is a set of rules that governs how data is formatted, transmitted, and received in a network. [cite: 11]
8.  **Can Wireshark decrypt encrypted traffic?**
    Wireshark itself cannot decrypt encrypted traffic (like HTTPS) without access to the session keys or private keys used for encryption. 
