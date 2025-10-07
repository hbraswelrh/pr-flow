---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.3.a10
      description: Rule for sys-1.3.a10
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_3_rhel9-elevated
    href: trestle://profiles/rhel9-bsi_sys_1_3_rhel9-elevated/profile.json
  sort-id: sys-01.03.a10
---

# sys-1.3.a10 - \[REPLACE_ME\] Preventing Further Intrusion When Vulnerabilities Are Exploited

## Control Statement

(1) Services and applications SHOULD be protected with individual security architecture (e.g.
with AppArmor or SELinux). (2) In addition, chroot environments and LXC or Docker containers
SHOULD be taken into account here. (3) It SHOULD be ensured that the standard profiles and
rules provided are activated.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.3.a10 -->

### Rules:

  - rule-sys-1.3.a10

### Implementation Status: planned

______________________________________________________________________
