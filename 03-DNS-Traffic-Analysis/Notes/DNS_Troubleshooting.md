# DNS Troubleshooting Summary

## Scenario

A user reported that websites could not be accessed by hostname.

---

## Investigation

Captured DNS traffic using Wireshark while performing multiple DNS lookups.

Commands executed:

```cmd
nslookup microsoft.com
nslookup github.com
nslookup openai.com
```

---

## Client

Windows 11 Pro

---

## DNS Server

<Record the DNS server IP observed in Wireshark>

---

## DNS Queries

- microsoft.com
- github.com
- openai.com

---

## Record Types Observed

- A
- AAAA

---

## Result

DNS queries were successfully resolved.

The DNS server returned valid IP addresses for all requested domains.

---

## Conclusion

DNS name resolution was functioning correctly.

No DNS errors or failed responses were observed during packet analysis.