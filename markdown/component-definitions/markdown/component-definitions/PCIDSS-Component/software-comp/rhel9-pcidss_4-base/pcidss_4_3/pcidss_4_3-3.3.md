---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_3-3.3
      description: Rule for pcidss_4_3-3.3
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_3-03.03
---

# pcidss_4_3-3.3 - \[REPLACE_ME\] Additional Requirement For Issuers And Companies That Support Issuing Services And Store Sensitive Authentication Data.

## Control Statement

Additional requirement for issuers and companies that support issuing services and store
sensitive authentication data: Any storage of sensitive authentication data is:
- Limited to that which is needed for a legitimate issuing business need and is secured.
- Encrypted using strong cryptography. This bullet is a best practice until until
31 March 2025, after which it will be required as part of Requirement 3.3.3 and must be
fully considered during a PCI DSS assessment.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_3-3.3 -->

### Rules:

  - rule-pcidss_4_3-3.3

### Implementation Status: planned

______________________________________________________________________
