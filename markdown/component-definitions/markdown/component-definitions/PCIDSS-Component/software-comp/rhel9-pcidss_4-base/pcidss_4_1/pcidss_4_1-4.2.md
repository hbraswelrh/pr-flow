---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_1-4.2
      description: Rule for pcidss_4_1-4.2
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_1-04.02
---

# pcidss_4_1-4.2 - \[REPLACE_ME\] Inbound Traffic From Untrusted Networks To Trusted Networks Is Restricted.

## Control Statement

Inbound traffic from untrusted networks to trusted networks is restricted to:
- Communications with system components that are authorized to provide publicly accessible
services, protocols, and ports.
- Stateful responses to communications initiated by system components in a trusted network.
- All other traffic is denied.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_1-4.2 -->

### Rules:

  - rule-pcidss_4_1-4.2

### Implementation Status: planned

______________________________________________________________________
