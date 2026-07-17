# Enterprise Network Troubleshooting Analysis

## Overview

This project demonstrates a structured approach to diagnosing network connectivity issues using built-in Windows networking tools. Wireshark was used alongside Windows commands to observe network traffic and verify successful communication.

## Diagnostic Commands

### ipconfig /all

Verified:

- IPv4 Address
- Subnet Mask
- Default Gateway
- DNS Server
- Network Adapter Configuration

The system received valid network configuration information.

---

### ping

Connectivity tests were performed against:

- Default Gateway
- Public IP Address (8.8.8.8)

Successful replies confirmed:

- Local network connectivity
- Internet connectivity

---

### nslookup

DNS queries successfully resolved domain names.

This confirmed:

- DNS server availability
- Successful name resolution

---

### tracert

Traceroute displayed the network path toward the destination host.

This demonstrated:

- Hop-by-hop routing
- Successful packet forwarding

---

### netstat

Displayed:

- Active TCP connections
- Listening ports
- Process IDs (PIDs)

Useful for identifying active network sessions and troubleshooting connectivity issues.

---

## Wireshark Analysis

Observed protocols included:

- ICMP
- DNS
- TCP

The captured traffic matched the Windows diagnostic commands executed during troubleshooting.

## Conclusion

The troubleshooting process confirmed that the computer had valid IP configuration, working DNS resolution, successful local and Internet connectivity, and active TCP communication. Combining Windows networking utilities with Wireshark provides an effective method for diagnosing common network issues in enterprise environments.