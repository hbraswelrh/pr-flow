---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_6-4.1
      description: Rule for pcidss_4_6-4.1
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_6-04.01
---

# pcidss_4_6-4.1 - \[REPLACE_ME\] For Public-Facing Web Applications, New Threats And Vulnerabilities Are Addressed On An Ongoing Basis And These Applications Are Protected Against Known Attacks.

## Control Statement

For public-facing web applications, new threats and vulnerabilities are addressed on an
ongoing basis and these applications are protected against known attacks as follows:
- Reviewing public-facing web applications via manual or automated application
vulnerability security assessment tools or methods as follows:
  - At least once every 12 months and after significant changes.
  - By an entity that specializes in application security.
  - Including, at a minimum, all common software attacks in Requirement 6.2.4.
  - All vulnerabilities are ranked in accordance with requirement 6.3.1.
  - All vulnerabilities are corrected.
  - The application is re-evaluated after the corrections
OR
- Installing an automated technical solution(s) that continually detects and prevents
web-based attacks as follows:
  - Installed in front of public-facing web applications to detect and prevent web-based
  attacks.
  - Actively running and up to date as applicable.
  - Generating audit logs.
  - Configured to either block web-based attacks or generate an alert that is immediately
  investigated.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_6-4.1 -->

### Rules:

  - rule-pcidss_4_6-4.1

### Implementation Status: planned

______________________________________________________________________
