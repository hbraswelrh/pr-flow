---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.1.a25
      description: Rule for sys-1.1.a25
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_1_rhel9-standard
    href: trestle://profiles/rhel9-bsi_sys_1_1_rhel9-standard/profile.json
  sort-id: sys-01.01.a25
---

# sys-1.1.a25 - \[REPLACE_ME\] Controlled Decommissioning Of A Server

## Control Statement

(1) When decommissioning a server, it SHOULD be ensured that no important data that might
still be present on the storage media is lost and no sensitive data remains.
(2) There SHOULD be an overview of the data stored in each location on the server.
(3) Furthermore, it SHOULD be ensured that services offered by the server will be taken over
by another server when necessary.
(4) A checklist SHOULD be created that is to be completed when decommissioning a server.
(5) This checklist SHOULD at least include aspects related to backing up data, migrating
services, and subsequently deleting all data in a secure manner.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.1.a25 -->

### Rules:

  - rule-sys-1.1.a25

### Implementation Status: planned

______________________________________________________________________
