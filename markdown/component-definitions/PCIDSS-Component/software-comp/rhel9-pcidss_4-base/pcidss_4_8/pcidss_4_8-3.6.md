---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_8-3.6
      description: Rule for pcidss_4_8-3.6
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_8-03.06
---

# pcidss_4_8-3.6 - \[REPLACE_ME\] If Passwords/Passphrases Are Used As Authentication Factors To Meet Requirement 8.3.1, They Meet The Minimum Level Of Complexity.

## Control Statement

- A minimum length of 12 characters (or IF the system does not support 12 characters, a
minimum length of eight characters).
- Contain both numeric and alphabetic characters.
A guessed password/passphrase cannot be verified by either an online or offline brute
force attack.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_8-3.6 -->

### Rules:

  - rule-pcidss_4_8-3.6

### Implementation Status: planned

______________________________________________________________________
