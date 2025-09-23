---
x-trestle-global:
  sort-id: req-02.02.03
---

# req-2.2.3 - \[REPLACE_ME\] 2.2.3 Implement Additional Security Features For Any Required Services, Protocols, Or Daemons That Are Considered To Be Insecure

## Control Statement

for example, use secured technologies such as SSH, S-FTP, TLS, or IPSec
VPN to protect insecure services such as NetBIOS, file-sharing, Telnet, FTP, etc.

Note: SSL and early TLS are not considered strong cryptography and
cannot be used as a security control after June 30, 2016. Prior to this date,
existing implementations that use SSL and/or early TLS must have a formal Risk
Mitigation and Migration Plan in place.

Effective immediately, new implementations must not use SSL or early TLS.

POS POI terminals (and the SSL/TLS termination points to which they connect) that
can be verified as not being susceptible to any known exploits for SSL and early
TLS may continue using these as a security control after June 30, 2016.'
