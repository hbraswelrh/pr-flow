---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.6.a16
      description: Rule for sys-1.6.a16
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-standard
    href: trestle://profiles/rhel9-bsi_sys_1_6-standard/profile.json
  sort-id: sys-01.06.a16
---

# sys-1.6.a16 - \[REPLACE_ME\] Administrative Remote Access To Containers

## Control Statement

(1)In principle, administrative access from a container to the container host and vice versa SHOULD be considered as administrative remote access. (2) Remote administrative access SHOULD NOT be established from a container to the container host. (3) Application containers SHOULD NOT contain remote maintenance access points. (4) Administrative access to application containers SHOULD always be carried out via the container runtime.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.6.a16 -->

### Rules:

  - rule-sys-1.6.a16

### Implementation Status: planned

______________________________________________________________________
