---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.6.a3
      description: Rule for sys-1.6.a3
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-standard
    href: trestle://profiles/rhel9-bsi_sys_1_6-standard/profile.json
  sort-id: sys-01.06.a3
---

# sys-1.6.a3 - \[REPLACE_ME\] Secure Use Of Containerised It Systems

## Control Statement

(1) In the case of containerised IT systems, consideration MUST be given to how containerisation affects the IT systems and applications operated, in particular the management and suitability of the applications. (2) Based on the protection needs of the applications, it MUST be checked whether the requirements for isolation and encapsulation of the containerised IT systems, virtual networks, and operated applications are sufficiently fulfilled. (3) The mechanisms of the operating system in question SHOULD be included in this check. (4) Since the host performs the function of a network component for virtual networks, the modules of the sub-layers NET.1 Networks and NET.3 Network Components MUST be considered accordingly. (5) Logical and overlay networks MUST also be considered and modelled. (6) Furthermore, the containerised IT systems used MUST meet the requirements at hand regarding availability and data throughput.(7) During operation, the performance and the state of the containerised IT systems SHOULD be monitored (health checks).

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.6.a3 -->

### Rules:

  - rule-sys-1.6.a3

### Implementation Status: planned

______________________________________________________________________
