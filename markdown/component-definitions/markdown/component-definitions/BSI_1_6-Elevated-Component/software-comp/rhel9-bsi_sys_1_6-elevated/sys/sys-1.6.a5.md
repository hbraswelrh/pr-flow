---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.6.a5
      description: Rule for sys-1.6.a5
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-elevated
    href: trestle://profiles/rhel9-bsi_sys_1_6-elevated/profile.json
  sort-id: sys-01.06.a5
---

# sys-1.6.a5 - \[REPLACE_ME\] Separation Of Administration And Access Networks For Containers

## Control Statement

(1) Networks for the administration of the host, the administration of the containers, and their access networks MUST be separated according to the protection needs at hand. (2) In principle, at least the administration of the host SHOULD only be possible from the administration network. (3) Only the communication relationships necessary for operation SHOULD be allowed.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.6.a5 -->

### Rules:

  - rule-sys-1.6.a5

### Implementation Status: planned

______________________________________________________________________
