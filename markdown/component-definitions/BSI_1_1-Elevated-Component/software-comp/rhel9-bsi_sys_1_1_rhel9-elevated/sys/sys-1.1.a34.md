---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.1.a34
      description: Rule for sys-1.1.a34
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_1_rhel9-elevated
    href: trestle://profiles/rhel9-bsi_sys_1_1_rhel9-elevated/profile.json
  sort-id: sys-01.01.a34
---

# sys-1.1.a34 - \[REPLACE_ME\] Hard Disk Encryption

## Control Statement

(1) In case of increased protection needs, a server's storage media should be encrypted using a
product or procedure that is considered secure. (2) This SHOULD also apply to virtual machines
containing production data. (3) Trusted Platform Module (TPM) SHOULD NOT be the only form
of key protection used. (4) Recovery passwords SHOULD be stored in an appropriate and secure
location. (5) In case of very high requirements (e.g. regarding confidentiality), full volume or full
disk encryption SHOULD be used.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.1.a34 -->

### Rules:

  - rule-sys-1.1.a34

### Implementation Status: planned

______________________________________________________________________
