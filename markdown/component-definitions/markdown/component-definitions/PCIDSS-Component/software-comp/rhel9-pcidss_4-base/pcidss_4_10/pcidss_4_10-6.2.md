---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_10-6.2
      description: Rule for pcidss_4_10-6.2
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_10-06.02
---

# pcidss_4_10-6.2 - \[REPLACE_ME\] Systems Are Configured To The Correct And Consistent Time.

## Control Statement

- One or more designated time servers are in use.
- Only the designated central time server(s) receives time from external sources.
- Time received from external sources is based on International Atomic Time or Coordinated
  Universal Time (UTC).
- The designated time server(s) accept time updates only from specific industry-accepted
  external sources.
- Where there is more than one designated time server, the time servers peer with one
  another to keep accurate time.
- Internal systems receive time information only from designated central time server(s).

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_10-6.2 -->

### Rules:

  - rule-pcidss_4_10-6.2

### Implementation Status: planned

______________________________________________________________________
