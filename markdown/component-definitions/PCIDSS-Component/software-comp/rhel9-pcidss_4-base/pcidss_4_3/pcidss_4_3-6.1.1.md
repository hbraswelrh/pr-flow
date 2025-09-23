---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_3-6.1.1
      description: Rule for pcidss_4_3-6.1.1
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_3-06.01.01
---

# pcidss_4_3-6.1.1 - \[REPLACE_ME\] Additional Requirement For Service Providers Only: A Documented Description Of The Cryptographic Architecture Is Maintained

## Control Statement

Additional requirement for service providers only: A documented description of the
cryptographic architecture is maintained that includes:
- Details of all algorithms, protocols, and keys used for the protection of stored
account data, including key strength and expiry date.
- Preventing the use of the same cryptographic keys in production and test environments.
This bullet is a best practice until 31 March 2025, after which it will be required as
part of Requirement 3.6.1.1 and must be fully considered during a PCI DSS assessment.
- Description of the key usage for each key.
- Inventory of any hardware security modules (HSMs), key management systems (KMS), and
other secure cryptographic devices (SCDs) used for key management, including type and
location of devices, as outlined in Requirement 12.3.4.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_3-6.1.1 -->

### Rules:

  - rule-pcidss_4_3-6.1.1

### Implementation Status: planned

______________________________________________________________________
