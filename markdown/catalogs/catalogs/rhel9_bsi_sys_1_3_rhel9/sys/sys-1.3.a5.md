---
x-trestle-global:
  sort-id: sys-01.03.a5
---

# sys-1.3.a5 - \[REPLACE_ME\] Secure Installation Of Software Packages

## Control Statement

(1) If software to be installed is to be compiled from source code, it MUST ONLY be unpacked,
configured, and compiled using an unprivileged user account. (2) The software to be installed
MUST NOT then be installed in the root file system of the server in question in an
uncontrolled manner.

(3) If the software is compiled from the source text, the selected parameters SHOULD be
documented appropriately. (4) Based on this documentation, it SHOULD be possible to compile
the software in a transparent and reproducible manner at any time. (5) All further installation
steps SHOULD also be documented.
