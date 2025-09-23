---
x-trestle-global:
  sort-id: req-03.04
---

# req-3.4 - \[REPLACE_ME\] 3.4 Render Pan Unreadable Anywhere It Is Stored (Including On Portable Digital Media, Backup Media, And In Logs) By Using Any Of The Following Approaches:

## Control Statement

* One-way hashes based on strong cryptography, (hash must be of the entire PAN)
* Truncation (hashing cannot be used to replace the truncated segment of PAN)
* Index tokens and pads (pads must be securely stored)
* Strong cryptography with associated key-management processes and procedures.

Note: It is a relatively trivial effort for a malicious individual to
reconstruct original PAN data if they have access to both the
truncated and hashed version of a PAN. Where hashed and truncated versions of
the same PAN are present in an entity's environment, additional controls
must be in place to ensure that the hashed and truncated versions cannot be
correlated to reconstruct the original PAN.
