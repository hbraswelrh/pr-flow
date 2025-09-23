---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_3-4.1
      description: Rule for pcidss_4_3-4.1
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_3-04.01
---

# pcidss_4_3-4.1 - \[REPLACE_ME\] Pan Is Masked When Displayed (The Bin And Last Four Digits Are The Maximum Number Of Digits To Be Displayed), Such That Only Personnel With A Legitimate Business Need Can See More Than The Bin And Last Four Digits Of The Pan.

## Control Statement

PAN displays are restricted to the minimum number of digits necessary to meet a defined
business need. This requirement does not supersede stricter requirements in place for
displays of cardholder data — for example, legal or payment brand requirements for
point-of-sale (POS) receipts. This requirement relates to protection of PAN where it is
displayed on screens, paper receipts, printouts, etc., and is not to be confused with
Requirement 3.5.1 for protection of PAN when stored, processed, or transmitted.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_3-4.1 -->

### Rules:

  - rule-pcidss_4_3-4.1

### Implementation Status: planned

______________________________________________________________________
