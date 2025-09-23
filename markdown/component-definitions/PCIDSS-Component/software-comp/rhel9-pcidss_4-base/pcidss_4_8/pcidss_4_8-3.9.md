---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_8-3.9
      description: Rule for pcidss_4_8-3.9
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_8-03.09
---

# pcidss_4_8-3.9 - \[REPLACE_ME\] If Passwords/Passphrases Are Used As The Only Authentication Factor For User Access (I.E., In Any Single-Factor Authentication Implementation) They Should Have A Limited Lifetime.

## Control Statement

If passwords/passphrases are used as the only authentication factor for user access (i.e.,
in any single-factor authentication implementation) then either:
- Passwords/passphrases are changed at least once every 90 days,
OR
- The security posture of accounts is dynamically analyzed, and real-time access to
resources is automatically determined accordingly.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_8-3.9 -->

### Rules:

  - rule-pcidss_4_8-3.9

### Implementation Status: planned

______________________________________________________________________
