# Web Traffic Troubleshooting Summary

## Scenario

A user reported difficulty accessing a website.

## Investigation

Captured HTTP and HTTPS traffic while accessing:

- http://neverssl.com
- https://example.com

## Protocols Observed

- HTTP
- TLS
- TCP
- DNS

## Result

HTTP traffic was transmitted in plain text.

HTTPS traffic successfully completed the TLS handshake before encrypted communication began.

## Conclusion

Both HTTP and HTTPS communication completed successfully. No transport-layer or encryption-related issues were observed during the investigation.