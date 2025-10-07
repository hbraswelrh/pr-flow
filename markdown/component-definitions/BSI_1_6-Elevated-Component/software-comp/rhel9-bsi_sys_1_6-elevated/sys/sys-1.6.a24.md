---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.6.a24
      description: Rule for sys-1.6.a24
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-elevated
    href: trestle://profiles/rhel9-bsi_sys_1_6-elevated/profile.json
  sort-id: sys-01.06.a24
---

# sys-1.6.a24 - \[REPLACE_ME\] Host-Based Attack Detection

## Control Statement

(1) The behaviour of containers and the applications or services running in them SHOULD be monitored. (2) Deviations from normal behaviour SHOULD be noticed and reported. (3) The reports SHOULD be handled appropriately in a centralised process for security incident handling. (4) At minimum, the behaviour to be monitored SHOULD cover:
  (5) • Network connections
  (6) • Created processes
  (7) • File system access attempts
  (8) • Kernel requests (syscalls)

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.6.a24 -->

### Rules:

  - rule-sys-1.6.a24

### Implementation Status: planned

______________________________________________________________________
