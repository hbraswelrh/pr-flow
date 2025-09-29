---
x-trestle-global:
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
