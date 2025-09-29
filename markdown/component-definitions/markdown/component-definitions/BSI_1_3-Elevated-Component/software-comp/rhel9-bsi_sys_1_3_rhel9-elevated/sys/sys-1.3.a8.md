---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.3.a8
      description: Rule for sys-1.3.a8
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_3_rhel9-elevated
    href: trestle://profiles/rhel9-bsi_sys_1_3_rhel9-elevated/profile.json
  sort-id: sys-01.03.a8
---

# sys-1.3.a8 - \[REPLACE_ME\] Encrypted Access Via Secure Shell

## Control Statement

(1) Only Secure Shell (SSH) SHOULD be used to create an encrypted and authenticated interactive
connection between two IT systems. (2) All other protocols whose functions are covered by
Secure Shell SHOULD be disabled completely. (3) For authentication, users SHOULD primarily
use certificates instead of passwords.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.3.a8 -->

### Rules:

  - rule-sys-1.3.a8

### Implementation Status: planned

______________________________________________________________________
