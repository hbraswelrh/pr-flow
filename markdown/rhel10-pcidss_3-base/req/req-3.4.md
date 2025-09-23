---
x-trestle-global:
  profile:
    title: rhel10-pcidss_3-base
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

# Editable Content

<!-- Make additions and edits below -->
<!-- The above represents the contents of the control as received by the profile, prior to additions. -->
<!-- If the profile makes additions to the control, they will appear below. -->
<!-- The above markdown may not be edited but you may edit the content below, and/or introduce new additions to be made by the profile. -->
<!-- If there is a yaml header at the top, parameter values may be edited. Use --set-parameters to incorporate the changes during assembly. -->
<!-- The content here will then replace what is in the profile for this control, after running profile-assemble. -->
<!-- The current profile has no added parts for this control, but you may add new ones here. -->
<!-- Each addition must have a heading either of the form ## Control my_addition_name -->
<!-- or ## Part a. (where the a. refers to one of the control statement labels.) -->
<!-- "## Control" parts are new parts added after the statement part. -->
<!-- "## Part" parts are new parts added into the top-level statement part with that label. -->
<!-- Subparts may be added with nested hash levels of the form ### My Subpart Name -->
<!-- underneath the parent ## Control or ## Part being added -->
<!-- See https://oscal-compass.github.io/compliance-trestle/tutorials/ssp_profile_catalog_authoring/ssp_profile_catalog_authoring for guidance. -->
