---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.3.a2
      description: Rule for sys-1.3.a2
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_3_rhel9-standard
    href: trestle://profiles/rhel9-bsi_sys_1_3_rhel9-standard/profile.json
  sort-id: sys-01.03.a2
---

# sys-1.3.a2 - \[REPLACE_ME\] Careful Allocation Of Ids

## Control Statement

(1) Each login name, each user ID (UID) and each group ID (GID) MUST ONLY be used once.
(2) Every user MUST be a member of at least one group. (3) Every GID mentioned in the /etc/passwd
file MUST be defined in the /etc/group file. (4) Every group SHOULD only contain the users that
are absolutely necessary. (5) In networked systems, care MUST also be taken to ensure that user
and group names (UIDs and GIDs) are assigned consistently in the system network if there is a
possibility that the same UIDs or GIDs could be assigned to different user or group names on
the systems during cross-system access.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.3.a2 -->

### Rules:

  - rule-sys-1.3.a2

### Implementation Status: planned

______________________________________________________________________
