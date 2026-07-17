# Project 06 – ICMP Traffic Analysis

## Overview

This project demonstrates how Internet Control Message Protocol (ICMP) traffic can be captured and analyzed using Wireshark.

A ping test was performed from a Windows 11 client to `8.8.8.8`. The resulting Echo Request and Echo Reply packets were examined to confirm successful network connectivity and understand how ICMP operates at the packet level.

## Objectives

- Generate ICMP traffic using the `ping` command
- Capture ICMP packets with Wireshark
- Identify Echo Request and Echo Reply messages
- Analyze ICMP type, source, and destination information
- Confirm successful connectivity and packet delivery

## Lab Environment

- Host: MacBook Air M4
- Hypervisor: VMware Fusion
- Client: Windows 11 Pro
- Packet Analyzer: Wireshark
- Destination: `8.8.8.8`

## Traffic Generation

The following command was executed from Windows Command Prompt:

```cmd
ping 8.8.8.8
```

## Wireshark Filter

The following display filter was applied:

```text
icmp
```

## Packet Analysis

The capture showed both ICMP Echo Request and Echo Reply packets.

- Echo Request: Type 8
- Echo Reply: Type 0
- Four requests were transmitted
- Four replies were received
- No packet loss was observed
- Successful replies confirmed network connectivity

## Screenshot

![ICMP Echo Request and Reply](Screenshots/01_ICMP_Request_Reply.png)

## Project Structure

```text
06-ICMP-Traffic-Analysis
├── README.md
├── Captures
│   └── icmp-analysis.pcapng
├── Notes
│   └── Analysis.md
└── Screenshots
    └── 01_ICMP_Request_Reply.png
```

## Skills Demonstrated

- Wireshark packet capture
- ICMP protocol analysis
- Echo Request and Echo Reply identification
- Basic network connectivity testing
- Packet-level troubleshooting
- Technical documentation

## Conclusion

This project demonstrated how ICMP is used to test network connectivity. By capturing and analyzing Echo Request and Echo Reply packets in Wireshark, the lab confirmed successful communication between the Windows 11 client and the destination host.