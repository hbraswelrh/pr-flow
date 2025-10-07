---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.1.a6
      description: Rule for sys-1.1.a6
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_1_rhel9-standard
    href: trestle://profiles/rhel9-bsi_sys_1_1_rhel9-standard/profile.json
  sort-id: sys-01.01.a6
---

# sys-1.1.a6 - \[REPLACE_ME\] Disabling Unnecessary Services

## Control Statement

(1) All unnecessary services and applications — particularly network services — MUST be
disabled or uninstalled. (2) All unused functions in firmware MUST also be disabled.
(3) On servers, the disk space allotted to both individual users and applications SHOULD be
restricted appropriately.
(4) The decisions taken in this regard SHOULD be documented in a way that makes it clear which
configuration and software equipment was chosen for servers.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.1.a6 -->

### Rules:

  - rule-sys-1.1.a6

### Implementation Status: planned

______________________________________________________________________
