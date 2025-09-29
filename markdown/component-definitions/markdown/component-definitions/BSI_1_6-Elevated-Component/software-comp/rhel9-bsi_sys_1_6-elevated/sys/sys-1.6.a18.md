---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.6.a18
      description: Rule for sys-1.6.a18
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-elevated
    href: trestle://profiles/rhel9-bsi_sys_1_6-elevated/profile.json
  sort-id: sys-01.06.a18
---

# sys-1.6.a18 - \[REPLACE_ME\] Application Services Accounts

## Control Statement

(1) System accounts within a container SHOULD have no permissions on the host system. (2) If such authorisation is required for operational reasons, it SHOULD only apply to the data and system access that is absolutely necessary. (3) The account in the container that is necessary to exchange data SHOULD be known in the host system

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.6.a18 -->

### Rules:

  - rule-sys-1.6.a18

### Implementation Status: planned

______________________________________________________________________
