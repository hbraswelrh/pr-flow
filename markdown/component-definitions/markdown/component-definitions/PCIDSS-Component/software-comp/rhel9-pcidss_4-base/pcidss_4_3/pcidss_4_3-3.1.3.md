---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_3-3.1.3
      description: Rule for pcidss_4_3-3.1.3
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_3-03.01.03
---

# pcidss_4_3-3.1.3 - \[REPLACE_ME\] The Personal Identification Number (Pin) And The Pin Block Are Not Stored Upon Completion Of The Authorization Process.

## Control Statement

This requirement is not eligible for the customized approach. PIN blocks are encrypted
during the natural course of transaction processes, but even if an entity encrypts the
PIN block again, it is still not allowed to be stored after the completion of the
authorization process.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_3-3.1.3 -->

### Rules:

  - rule-pcidss_4_3-3.1.3

### Implementation Status: planned

______________________________________________________________________
