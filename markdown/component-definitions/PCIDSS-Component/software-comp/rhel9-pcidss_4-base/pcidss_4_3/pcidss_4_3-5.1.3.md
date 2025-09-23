---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_3-5.1.3
      description: Rule for pcidss_4_3-5.1.3
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_3-05.01.03
---

# pcidss_4_3-5.1.3 - \[REPLACE_ME\] If Disk-Level Or Partition-Level Encryption Is Used (Rather Than File-, Column-, Or Field--Level Database Encryption) To Render Pan Unreadable, It Is Managed.

## Control Statement

If disk-level or partition-level encryption is used (rather than file-, column-, or
field--level database encryption) to render PAN unreadable, it is managed as follows:
- Logical access is managed separately and independently of native operating system
authentication and access control mechanisms.
- Decryption keys are not associated with user accounts.
- Authentication factors (passwords, passphrases, or cryptographic keys) that allow
access to unencrypted data are stored securely.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_3-5.1.3 -->

### Rules:

  - rule-pcidss_4_3-5.1.3

### Implementation Status: planned

______________________________________________________________________
