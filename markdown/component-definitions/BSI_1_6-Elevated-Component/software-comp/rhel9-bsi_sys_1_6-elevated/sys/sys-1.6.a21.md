---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-sys-1.6.a21
      description: Rule for sys-1.6.a21
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-elevated
    href: trestle://profiles/rhel9-bsi_sys_1_6-elevated/profile.json
  sort-id: sys-01.06.a21
---

# sys-1.6.a21 - \[REPLACE_ME\] Extended Security Policies

## Control Statement

(1) Extended policies SHOULD restrict the permissions of containers. (2) Mandatory Access Control (MAC) or a comparable technology SHOULD enforce these policies. (3) At minimum, policies SHOULD restrict the following types of access: • Incoming and outgoing network connections • File system access attempts • Kernel requests (syscalls) (4) A runtime SHOULD start containers in such a way that the kernel of the host system prevents all activities of the containers that are not allowed by the relevant policy (e.g. by setting up local packet filters or revoking permissions), or at least reports violations appropriately.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: sys-1.6.a21 -->

### Rules:

  - rule-sys-1.6.a21

### Implementation Status: planned

______________________________________________________________________
