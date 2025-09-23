---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_3-3.1.1
      description: Rule for pcidss_4_3-3.1.1
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_3-03.01.01
---

# pcidss_4_3-3.1.1 - \[REPLACE_ME\] The Full Contents Of Any Track Are Not Stored Upon Completion Of The Authorization Process.

## Control Statement

This requirement is not eligible for the customized approach. In the normal course of
business, the following data elements from the track may need to be retained:
- Cardholder name.
- Primary account number (PAN).
- Expiration date.
- Service code.
To minimize risk, store securely only these data elements as needed for business.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_3-3.1.1 -->

### Rules:

  - rule-pcidss_4_3-3.1.1

### Implementation Status: planned

______________________________________________________________________
