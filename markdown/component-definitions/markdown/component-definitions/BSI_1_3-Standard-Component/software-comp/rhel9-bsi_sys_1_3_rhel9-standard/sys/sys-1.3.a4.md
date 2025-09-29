---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.3.a4
      description: Rule for sys-1.3.a4
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_3_rhel9-standard
    href: trestle://profiles/rhel9-bsi_sys_1_3_rhel9-standard/profile.json
  sort-id: sys-01.03.a4
---

# sys-1.3.a4 - \[REPLACE_ME\] Protection From Exploitation Of Vulnerabilities In Applications

## Control Statement

(1) ASLR and DEP/NX MUST be activated in the kernel and used by applications to make it harder
to exploit vulnerabilities in applications. (2) Security functions of the kernel and of the standard
libraries (such as heap and stack protection) MUST NOT be disabled.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.3.a4 -->

### Rules:

  - rule-sys-1.3.a4

### Implementation Status: planned

______________________________________________________________________
