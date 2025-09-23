---
x-trestle-global:
  sort-id: req-04.01
---

# req-4.1 - \[REPLACE_ME\] 4.1 Use Strong Cryptography And Security Protocols (For Example, Tls, Ipsec, Ssh, Etc.) To Safeguard Sensitive Cardholder Data During Transmission Over Open, Public Networks, Including The Following:

## Control Statement

* Only trusted keys and certificates are accepted.
* The protocol in use only supports secure versions or configurations.
* The encryption strength is appropriate for the encryption methodology in
use.

Note: SSL and early TLS are not considered strong cryptography and cannot
be used as a security control after June 30, 2016. Prior to this date, existing
implementations that use SSL and/or early TLS must have a formal Risk Mitigation
and Migration Plan in place.

Effective immediately, new implementations must not use SSL or early TLS.

POS POI terminals (and the SSL/TLS termination points to which they connect)
that can be verified as not being susceptible to any known exploits for SSL
and early TLS may continue using these as a security control after
June 30, 2016.

Examples of open, public networks include but are not limited to:
* The Internet
* Wireless technologies, including 802.11 and Bluetooth
* Cellular technologies, for example, Global System for Mobile
communications (GSM), Code division multiple access (CDMA)
* General Packet Radio Service (GPRS)
* Satellite communications
