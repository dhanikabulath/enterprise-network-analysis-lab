# Project 02 - TCP Connection Analysis

## Overview

This project focuses on understanding the Transmission Control Protocol (TCP) by analyzing connection establishment, TCP header fields, connection termination, and common troubleshooting indicators using Wireshark.

The project demonstrates practical experience interpreting TCP communication in enterprise environments and understanding how reliable network connections are established and maintained.

---

# Objectives

- Capture TCP traffic
- Analyze the TCP three-way handshake
- Inspect TCP header fields
- Examine TCP connection termination
- Investigate TCP reset packets
- Analyze retransmissions
- Review duplicate acknowledgments
- Visualize TCP communication using stream graphs

---

# Environment

| Component | Configuration |
|-----------|---------------|
| Client | Windows 11 Pro |
| Analysis Tool | Wireshark |
| Capture Format | PCAPNG |
| Network | Home Lab |

---

# Lab 1 – TCP Packet Capture

Captured TCP traffic generated during web browsing.

**Capture**

- tcp_connection_capture.pcapng

**Screenshot**

- 01_TCP_Capture.png

---

# Lab 2 – TCP Three-Way Handshake

Analyzed TCP connection establishment by identifying:

- SYN
- SYN, ACK
- ACK

**Screenshot**

- 02_TCP_Three_Way_Handshake.png

---

# Lab 3 – TCP Header Analysis

Inspected the TCP header and reviewed:

- Source Port
- Destination Port
- Sequence Number
- Acknowledgment Number
- Window Size
- TCP Flags
- Checksum

**Screenshot**

- 03_TCP_Header.png

---

# Lab 4 – TCP Connection Termination

Observed normal TCP connection termination using FIN and ACK packets.

**Screenshot**

- 04_TCP_FIN_ACK.png

---

# Lab 5 – TCP Reset Analysis

Applied a display filter to identify TCP reset (RST) packets.

No TCP reset packets were observed during this capture, indicating normal connection behavior.

**Screenshot**

- 05_TCP_RST.png

---

# Lab 6 – TCP Retransmission Analysis

Applied retransmission analysis filters.

No retransmissions were observed during this capture, indicating stable network communication.

**Screenshot**

- 06_TCP_Retransmission.png

---

# Lab 7 – Duplicate ACK Analysis

Applied duplicate acknowledgment filters.

No duplicate acknowledgments were detected during this capture.

**Screenshot**

- 07_Duplicate_ACK.png

---

# Lab 8 – TCP Stream Graph Analysis

Reviewed TCP communication using Wireshark stream graphs.

**Screenshot**

- 08_TCP_Stream_Graph.png

---

# Skills Demonstrated

- TCP Packet Capture
- TCP Connection Analysis
- Three-Way Handshake Analysis
- TCP Header Inspection
- TCP Connection Termination
- TCP Troubleshooting
- Wireshark Display Filters
- Network Diagnostics

---

# Lessons Learned

This project provided practical experience analyzing TCP communication using Wireshark. Understanding how TCP connections are established, maintained, and terminated is fundamental for troubleshooting enterprise network issues and is a core networking skill for IT Support and Security Operations (SOC) professionals.

---

# Next Project

## Project 03 – DNS Traffic Analysis

The next project focuses on analyzing DNS queries and responses, name resolution, DNS record types, recursive lookups, and troubleshooting DNS-related connectivity issues using Wireshark.