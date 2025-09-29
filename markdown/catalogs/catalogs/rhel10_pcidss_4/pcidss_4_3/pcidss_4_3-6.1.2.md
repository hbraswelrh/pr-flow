---
x-trestle-global:
  sort-id: pcidss_4_3-06.01.02
---

# pcidss_4_3-6.1.2 - \[REPLACE_ME\] Secret And Private Keys Used To Encrypt/Decrypt Stored Account Data Are Stored In Secure Forms.

## Control Statement

Secret and private keys used to encrypt/decrypt stored account data are stored in one
(or more) of the following forms at all times:
- Encrypted with a key-encrypting key that is at least as strong as the data-encrypting
key, and that is stored separately from the data-encrypting key.
- Within a secure cryptographic device (SCD), such as a hardware security module (HSM)
or PTS-approved point-of-interaction device.
- As at least two full-length key components or key shares, in accordance with an
industry-accepted method.
Secret and private keys are stored in a secure form that prevents unauthorized retrieval
or access. It is not required that public keys be stored in one of these forms.
Cryptographic keys stored as part of a key management system (KMS) that employs SCDs are
acceptable. A cryptographic key that is split into two parts does not meet this
requirement. Secret or private keys stored as key components or key shares must be
generated via one of the following
