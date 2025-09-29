---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_1-3.3
      description: Rule for pcidss_4_1-3.3
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_1-03.03
---

# pcidss_4_1-3.3 - \[REPLACE_ME\] Nscs Are Installed Between All Wireless Networks And The Cde, Regardless Of Whether The Wireless Network Is A Cde.

## Control Statement

NSCs are installed between all wireless networks and the CDE, regardless of whether the
wireless network is a CDE, such that:
- All wireless traffic from wireless networks into the CDE is denied by default.
- Only wireless traffic with an authorized business purpose is allowed into the CDE.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_1-3.3 -->

### Rules:

  - rule-pcidss_4_1-3.3

### Implementation Status: planned

______________________________________________________________________
