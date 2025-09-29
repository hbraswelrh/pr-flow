---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_8-2.8
      description: Rule for pcidss_4_8-2.8
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_8-02.08
---

# pcidss_4_8-2.8 - \[REPLACE_ME\] If A User Session Has Been Idle For More Than 15 Minutes, The User Is Required To Re-Authenticate To Re-Activate The Terminal Or Session.

## Control Statement

A user session cannot be used except by the authorized user. This requirement is not
intended to apply to user accounts on point-of-sale terminals that have access to only one
card number at a time to facilitate a single transaction (such as IDs used by cashiers on
point-of-sale terminals). This requirement is not meant to prevent legitimate activities
from being performed while the console/PC is unattended.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_8-2.8 -->

### Rules:

  - rule-pcidss_4_8-2.8

### Implementation Status: planned

______________________________________________________________________
