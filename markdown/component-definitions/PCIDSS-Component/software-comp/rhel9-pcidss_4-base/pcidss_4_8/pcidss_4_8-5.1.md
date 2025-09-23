---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_8-5.1
      description: Rule for pcidss_4_8-5.1
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_8-05.01
---

# pcidss_4_8-5.1 - \[REPLACE_ME\] Mfa Systems Are Properly Implemented.

## Control Statement

- The MFA system is not susceptible to replay attacks.
- MFA systems cannot be bypassed by any users, including administrative users unless
specifically documented, and authorized by management on an exception basis, for a limited
time period.
- At least two different types of authentication factors are used.
- Success of all authentication factors is required before access is granted.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_8-5.1 -->

### Rules:

  - rule-pcidss_4_8-5.1

### Implementation Status: planned

______________________________________________________________________
