---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_8-2.1
      description: Rule for pcidss_4_8-2.1
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_8-02.01
---

# pcidss_4_8-2.1 - \[REPLACE_ME\] All Users Are Assigned A Unique Id Before Access To System Components Or Cardholder Data Is Allowed.

## Control Statement

All actions by all users are attributable to an individual. This requirement is not
intended to apply to user accounts within point-of-sale terminals that have access to only
one card number at a time to facilitate a single transaction (such as IDs used by cashiers
on point-of-sale terminals).

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_8-2.1 -->

### Rules:

  - rule-pcidss_4_8-2.1

### Implementation Status: planned

______________________________________________________________________
