---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_4-2.2
      description: Rule for pcidss_4_4-2.2
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
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

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_4-2.2 -->

### Rules:

  - rule-pcidss_4_4-2.2

### Implementation Status: planned

______________________________________________________________________
