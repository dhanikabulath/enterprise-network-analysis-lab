# TCP Header Fields

## Source Port
Identifies the client application initiating the connection.

## Destination Port
Identifies the destination service (e.g., 443 for HTTPS).

## Sequence Number
Tracks the order of transmitted bytes.

## Acknowledgment Number
Confirms receipt of data from the remote host.

## Window Size
Indicates how much data the receiver is prepared to accept.

## Flags
Control the state of the TCP connection.

Common flags include:

- SYN
- ACK
- FIN
- RST
- PSH
- URG

## Checksum
Used to verify packet integrity.