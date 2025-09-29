---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.6.a17
      description: Rule for sys-1.6.a17
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-standard
    href: trestle://profiles/rhel9-bsi_sys_1_6-standard/profile.json
  sort-id: sys-01.06.a17
---

# sys-1.6.a17 - \[REPLACE_ME\] Running Containers Without Privileges

## Control Statement

(1) A container runtime and any instantiated containers SHOULD only be executed by a non- privileged system account that does not have (and cannot gain) elevated rights to the container service or host operating system. (2) The container runtime SHOULD be encapsulated by additional measures, such as using the virtualisation extensions of CPUs. (3) If containers are to take over tasks of the host system in exceptional cases, privileges on the host system SHOULD be limited to the minimum necessary. (4)Exceptions SHOULD be adequately documented.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.6.a17 -->

### Rules:

  - rule-sys-1.6.a17

### Implementation Status: planned

______________________________________________________________________
