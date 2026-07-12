# Project 01 - Wireshark Fundamentals

## Overview

This project introduces the fundamentals of network packet analysis using Wireshark. It covers packet capture, protocol filtering, packet inspection, TCP stream analysis, and network statistics commonly used by IT Support Engineers and Security Operations (SOC) analysts.

The project demonstrates practical experience in capturing and analyzing enterprise network traffic using Wireshark.

---

# Objectives

- Install and configure Wireshark
- Capture live network traffic
- Apply protocol display filters
- Inspect packet structure
- Analyze TCP streams
- Review protocol hierarchy
- Examine network conversations
- Identify network endpoints

---

# Environment

| Component | Configuration |
|-----------|---------------|
| Client | Windows 11 Pro |
| Analysis Tool | Wireshark |
| Capture Format | PCAPNG |
| Network | Home Lab |

---

# Lab 1 – Wireshark Installation

Verified Wireshark installation and available capture interfaces.

**Screenshot**

- 01_Wireshark_Main_Window.png

---

# Lab 2 – First Packet Capture

Captured live network traffic and saved the capture for analysis.

**Capture**

- first_capture.pcapng

**Screenshot**

- 02_First_Capture.png

---

# Lab 3 – Wireshark Interface

Reviewed:

- Packet List
- Packet Details
- Packet Bytes

**Screenshot**

- 03_Wireshark_Interface.png

---

# Lab 4 – Display Filters

Applied filters for:

- DNS
- TCP
- UDP
- ICMP

**Screenshots**

- 04_DNS_Filter.png
- 05_TCP_Filter.png
- 06_UDP_Filter.png
- 07_ICMP_Filter.png

---

# Lab 5 – ICMP Traffic

Generated ICMP traffic using:

```cmd
ping 8.8.8.8
```

Saved:

- icmp_capture.pcapng

---

# Lab 6 – DNS Packet Analysis

Inspected:

- Ethernet II
- IPv4
- UDP
- DNS

**Screenshot**

- 08_DNS_Packet_Details.png

---

# Lab 7 – Packet Bytes

Reviewed hexadecimal packet contents.

**Screenshot**

- 09_Packet_Bytes.png

---

# Lab 8 – TCP Stream Analysis

Followed an entire TCP conversation between client and server.

**Screenshot**

- 10_TCP_Stream.png

---

# Lab 9 – Protocol Hierarchy

Reviewed protocol distribution within the capture.

**Screenshot**

- 11_Protocol_Hierarchy.png

---

# Lab 10 – Conversations

Analyzed communication sessions.

**Screenshot**

- 12_Conversations.png

---

# Lab 11 – Endpoints

Reviewed participating IP and MAC addresses.

**Screenshot**

- 13_Endpoints.png

---

# Skills Demonstrated

- Packet Capture
- Packet Inspection
- Protocol Analysis
- DNS Analysis
- TCP Analysis
- UDP Analysis
- ICMP Analysis
- TCP Stream Analysis
- Network Statistics
- Endpoint Identification
- Enterprise Network Troubleshooting

---

# Lessons Learned

This project establishes the foundation for enterprise network troubleshooting by demonstrating how to capture, inspect, and interpret network traffic using Wireshark. These skills are fundamental for diagnosing connectivity issues, understanding protocol behavior, and supporting enterprise IT environments.

---

# Next Project

## Project 02 - TCP Connection Analysis

Analyze the complete TCP connection lifecycle, including the three-way handshake, connection termination, retransmissions, and common TCP troubleshooting scenarios.