# ICMP Traffic Analysis

## Overview

Internet Control Message Protocol (ICMP) is a network layer protocol used for diagnostic and error-reporting purposes. It is commonly used by the `ping` utility to verify connectivity between network devices.

## Traffic Generated

The command below was executed:

```cmd
ping 8.8.8.8
```

The capture contained ICMP Echo Request and Echo Reply packets.

## Packet Analysis

### Echo Request

- ICMP Type: 8
- Purpose: Sent by the source device to determine whether the destination host is reachable.
- Source: Windows 11 Client
- Destination: 8.8.8.8

### Echo Reply

- ICMP Type: 0
- Purpose: Returned by the destination host to confirm successful connectivity.
- Source: 8.8.8.8
- Destination: Windows 11 Client

## Observations

- Four ICMP Echo Requests were transmitted.
- Four ICMP Echo Replies were received.
- No packet loss was observed.
- The replies confirmed successful network connectivity.
- Round-trip time (RTT) values indicated normal network latency.

## Conclusion

The packet capture demonstrates the operation of the ICMP protocol during a successful ping test. Wireshark was used to analyze both Echo Request and Echo Reply packets, confirming successful communication between the client and the destination host. This lab provides practical experience in network diagnostics and packet analysis using Wireshark.