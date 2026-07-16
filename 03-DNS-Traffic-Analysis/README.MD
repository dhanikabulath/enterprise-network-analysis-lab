# Project 03 - DNS Traffic Analysis

## Overview

This project demonstrates how to analyze Domain Name System (DNS) traffic using Wireshark. It focuses on capturing DNS queries and responses, examining DNS record types, identifying DNS servers, and troubleshooting name resolution issues commonly encountered in enterprise environments.

The project simulates a real-world IT Support scenario where users are unable to access websites due to DNS-related issues.

---

# Scenario

> **A user reports that websites cannot be accessed by hostname, although Internet connectivity is available.**

The objective is to verify whether DNS resolution is functioning correctly and identify the cause of the issue.

---

# Objectives

- Capture DNS traffic
- Filter DNS packets
- Analyze DNS queries
- Analyze DNS responses
- Identify DNS record types
- Review DNS conversations
- Identify DNS endpoints
- Perform DNS troubleshooting

---

# Environment

| Component | Configuration |
|-----------|---------------|
| Operating System | Windows 11 Pro |
| Analysis Tool | Wireshark |
| Capture Format | PCAPNG |
| Network | Home Lab |

---

# Project Structure

```text
03-DNS-Traffic-Analysis
│
├── Captures
├── Notes
├── Screenshots
└── README.MD
```

---

# Lab 1 – DNS Packet Capture

Generated DNS traffic using multiple **nslookup** queries.

### Capture

`Captures/dns_capture.pcapng`

### Screenshot

![DNS Capture](Screenshots/01_DNS_Capture.png)

---

# Lab 2 – DNS Display Filter

Applied the Wireshark DNS display filter to isolate DNS traffic.

Display Filter:

```text
dns
```

### Screenshot

![DNS Filter](Screenshots/02_DNS_Filter.png)

---

# Lab 3 – DNS Query Analysis

Inspected a DNS query packet and reviewed:

- Transaction ID
- Flags
- Query Name
- Query Type
- Questions

### Screenshot

![DNS Query](Screenshots/03_DNS_Query.png)

---

# Lab 4 – DNS Response Analysis

Reviewed the DNS response and verified:

- Response Code
- Returned IP Address
- Answer Count
- Time To Live (TTL)

### Screenshot

![DNS Response](Screenshots/04_DNS_Response.png)

---

# Lab 5 – DNS Record Types

Reviewed DNS record types returned by the DNS server.

Observed record types:

- A
- AAAA
- CNAME (if available)

### Screenshot

![DNS Record Types](Screenshots/05_DNS_Record_Types.png)

---

# Lab 6 – DNS Conversations

Reviewed UDP conversations generated during DNS communication.

### Screenshot

![DNS Conversations](Screenshots/06_DNS_Conversations.png)

---

# Lab 7 – DNS Endpoints

Reviewed the communicating client and DNS server endpoints.

### Screenshot

![DNS Endpoints](Screenshots/07_DNS_Endpoints.png)

---

# Lab 8 – DNS Troubleshooting Summary

Documented DNS troubleshooting findings.

Verified:

- Client IP Address
- DNS Server IP Address
- Queried Domains
- Returned IP Addresses
- DNS Resolution Status

---

# Skills Demonstrated

- DNS Packet Capture
- DNS Query Analysis
- DNS Response Analysis
- DNS Record Identification
- UDP Packet Analysis
- Wireshark Display Filters
- DNS Troubleshooting
- Enterprise Network Diagnostics

---

# Lessons Learned

This project provided practical experience analyzing DNS communication using Wireshark. Understanding DNS queries, responses, and record types is essential for diagnosing name resolution issues encountered in enterprise IT environments. These skills are fundamental for IT Support Engineers, Network Administrators, and Security Operations (SOC) analysts.

---

# Next Project

## Project 04 – DHCP Traffic Analysis

The next project focuses on analyzing DHCP Discover, Offer, Request, and Acknowledgment (DORA) messages to understand how IP addresses are dynamically assigned within enterprise networks.