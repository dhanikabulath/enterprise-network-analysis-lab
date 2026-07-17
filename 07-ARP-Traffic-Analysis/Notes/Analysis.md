# ARP Traffic Analysis

## Overview

Address Resolution Protocol (ARP) is used to resolve IPv4 addresses into MAC addresses on a local network. Before communication can occur on an Ethernet network, a device must determine the destination device's MAC address.

## Traffic Generated

The ARP cache was cleared using the `arp -d *` command, followed by a ping to the default gateway to generate ARP traffic.

## Packet Analysis

The capture contained both ARP Request and ARP Reply packets.

### ARP Request

- Opcode: Request (1)
- Purpose: Broadcast to discover the MAC address associated with the target IP address.
- Destination MAC: Broadcast (FF:FF:FF:FF:FF:FF)

### ARP Reply

- Opcode: Reply (2)
- Purpose: Returns the MAC address corresponding to the requested IP address.
- Destination: Requesting host

## Observations

- The client broadcast an ARP Request to locate the gateway.
- The gateway responded with an ARP Reply containing its MAC address.
- ARP communication occurred only within the local network segment.
- Successful address resolution enabled subsequent network communication.

## Conclusion

This lab demonstrated how ARP resolves IPv4 addresses into MAC addresses before Ethernet communication begins. Wireshark was used to observe both the ARP Request and ARP Reply packets, providing insight into Layer 2 address resolution within a local network.