---
x-trestle-global:
  sort-id: pcidss_4_4-02.02
---

# pcidss_4_4-2.2 - \[REPLACE_ME\] Pan Is Secured With Strong Cryptography Whenever It Is Sent Via End-User Messaging Technologies.

## Control Statement

Cleartext PAN cannot be read or intercepted from transmissions using end-user messaging
technologies. This requirement also applies if a customer, or other third-party, requests
that PAN is sent to them via end-user messaging technologies. There could be occurrences
where an entity receives unsolicited cardholder data via an insecure communication channel
that was not intended for transmissions of sensitive data. In this situation, the entity
can choose to either include the channel in the scope of their CDE and secure it according
to PCI DSS or delete the cardholder data and implement measures to prevent the channel
from being used for cardholder data.
