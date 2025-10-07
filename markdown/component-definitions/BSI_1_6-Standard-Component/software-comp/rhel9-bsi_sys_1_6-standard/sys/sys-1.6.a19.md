---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.6.a19
      description: Rule for sys-1.6.a19
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-standard
    href: trestle://profiles/rhel9-bsi_sys_1_6-standard/profile.json
  sort-id: sys-01.06.a19
---

# sys-1.6.a19 - \[REPLACE_ME\] Including Data Stores In Containers

## Control Statement

(1) Containers SHOULD ONLY be able to access the mass storage and directories necessary for operation. (2) Permissions SHOULD only be explicitly assigned where needed. (3) If the container runtime for a container includes local storage, the access rights in the file system SHOULD be restricted to the service account of the container. (4) If network storage is used, the permissions SHOULD be set on the network storage itself

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.6.a19 -->

### Rules:

  - rule-sys-1.6.a19

### Implementation Status: planned

______________________________________________________________________
