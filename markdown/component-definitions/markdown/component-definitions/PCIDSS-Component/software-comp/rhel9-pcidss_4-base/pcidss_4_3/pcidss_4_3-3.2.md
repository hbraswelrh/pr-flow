---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_3-3.2
      description: Rule for pcidss_4_3-3.2
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_3-03.02
---

# pcidss_4_3-3.2 - \[REPLACE_ME\] Sad That Is Stored Electronically Prior To Completion Of Authorization Is Encrypted Using Strong Cryptography.

## Control Statement

This requirement is not eligible for the customized approach. Whether SAD is permitted to
be stored prior to authorization is determined by the organizations that manage compliance
programs (for example, payment brands and acquirers). Contact the organizations of
interest for any additional criteria. This requirement applies to all storage of SAD, even
if no PAN is present in the environment. Refer to Requirement 3.2.1 for an additional
requirement that applies if SAD is stored prior to completion of authorization. Issuers
and companies that support issuing services, where there is a legitimate and documented
business need to store SAD, are not required to meet this requirement. A legitimate
business need is one that is necessary for the performance of the function being provided
by or for the issuer. Refer to Requirement 3.3.3 for requirements specifically for issuers.
This requirement does not replace how PIN blocks are required to be managed, nor does it
mean that a properly encrypted PIN block needs to be encrypted again.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_3-3.2 -->

### Rules:

  - rule-pcidss_4_3-3.2

### Implementation Status: planned

______________________________________________________________________
