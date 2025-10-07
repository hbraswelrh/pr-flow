---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.6.a8
      description: Rule for sys-1.6.a8
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-standard
    href: trestle://profiles/rhel9-bsi_sys_1_6-standard/profile.json
  sort-id: sys-01.06.a8
---

# sys-1.6.a8 - \[REPLACE_ME\] Secure Storage Of Container Access Data

## Control Statement

(1) Access data MUST be stored and managed in such a way that only authorised persons and containers can access it. (2) In particular, it MUST be ensured that access data is only stored in specially protected locations and not in images. (3) The access data management mechanisms provided by container service management software SHOULD be used. (4) At minimum, the following credentials MUST be stored securely: • Passwords of any accounts • API keys for services used by the application • Keys for symmetric encryption • Private keys for public key authentication

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.6.a8 -->

### Rules:

  - rule-sys-1.6.a8

### Implementation Status: planned

______________________________________________________________________
