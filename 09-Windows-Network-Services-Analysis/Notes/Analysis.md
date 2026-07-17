# Windows Network Services Analysis

## Overview

This project analyzes common Windows network services using Wireshark. Built-in Windows networking tools and web browsing activities were used to generate traffic for protocol analysis. The objective was to observe how Windows communicates with network services such as DNS, HTTPS, TCP, and Network Time Protocol (NTP).

## Traffic Generated

The following activities were performed:

- DNS lookup using `nslookup`
- Secure web browsing over HTTPS
- Windows time synchronization using `w32tm /resync`
- General TCP communication

## Packet Analysis

### DNS

DNS queries and responses were captured during domain name resolution.

Observed:

- Standard DNS Query
- Standard DNS Response
- Domain name resolution before establishing network connections

### HTTPS / TLS

HTTPS traffic was captured while accessing secure websites.

Observed:

- TCP three-way handshake
- TLS handshake
- Encrypted application data

### TCP

TCP packets demonstrated reliable communication between the client and remote servers.

Observed:

- SYN
- SYN-ACK
- ACK
- Data transfer
- Connection termination

### Network Time Protocol (NTP)

Windows synchronized the system clock with the configured time server.

Observed:

- Time synchronization request
- Time synchronization response

## Observations

- DNS successfully resolved hostnames into IP addresses.
- HTTPS connections were encrypted using TLS.
- TCP provided reliable communication for network sessions.
- Windows automatically communicated with network services during normal operation.
- Wireshark provided visibility into each stage of network communication.

## Conclusion

This project demonstrated how Windows interacts with essential network services during everyday operations. DNS, TCP, TLS, and NTP traffic were successfully captured and analyzed, providing practical experience with enterprise network communications and protocol analysis using Wireshark.