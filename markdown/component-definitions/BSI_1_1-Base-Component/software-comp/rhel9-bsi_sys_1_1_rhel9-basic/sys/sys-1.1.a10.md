---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.1.a10
      description: Rule for sys-1.1.a10
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_1_rhel9-basic
    href: trestle://profiles/rhel9-bsi_sys_1_1_rhel9-basic/profile.json
  sort-id: sys-01.01.a10
---

# sys-1.1.a10 - \[REPLACE_ME\] Logging

## Control Statement

(1) In general, all security-relevant system events MUST be logged, including the following at
minimum:
• (2) System starts and reboots
• (3) Successful and failed login attempts (operating system and application software)
• (4) Failed authorisation checks
• (5) Blocked data flows (violations of ACLs or firewall rules)
• (6) Creation of or changes to users, groups, and authorisations
• (7) Security-relevant error messages (e.g. hardware defects, exceeded capacity limits)
• (8) Warnings from security systems (e.g. virus protection)

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.1.a10 -->

### Rules:

  - rule-sys-1.1.a10

### Implementation Status: planned

______________________________________________________________________
