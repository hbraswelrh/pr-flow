---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_3-7.5
      description: Rule for pcidss_4_3-7.5
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_3-07.05
---

# pcidss_4_3-7.5 - \[REPLACE_ME\] Key Management Policies Procedures Are Implemented To Include The Retirement, Replacement, Or Destruction Of Keys Used To Protect Stored Account Data, As Deemed Necessary.

## Control Statement

Key management policies procedures are implemented to include the retirement, replacement,
or destruction of keys used to protect stored account data, as deemed necessary when:
- The key has reached the end of its defined cryptoperiod.
- The integrity of the key has been weakened, including when personnel with knowledge of a
cleartext key component leaves the company, or the role for which the key component was
known.
- The key is suspected of or known to be compromised.
- Retired or replaced keys are not used for encryption operations.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_3-7.5 -->

### Rules:

  - rule-pcidss_4_3-7.5

### Implementation Status: planned

______________________________________________________________________
