---
x-trestle-global:
  profile:
    title: rhel10-pcidss_4-base
  sort-id: pcidss_4_3-05.01.01
---

# pcidss_4_3-5.1.1 - \[REPLACE_ME\] Hashes Used To Render Pan Unreadable (Per The First Bullet Of Requirement 3.5.1) Are Keyed Cryptographic Hashes Of The Entire Pan, With Associated Key-Management Processes And Procedures In Accordance With Requirements 3.6 And 3.7.

## Control Statement

All Applicability Notes for Requirement 3.5.1 also apply to this requirement.
Key-management processes and procedures (Requirements 3.6 and 3.7) do not apply to
system components used to generate individual keyed hashes of a PAN for comparison to
another system if:
- The system components only have access to one hash value at a time (hash values are
not stored on the system)
AND
- There is no other account data stored on the same system as the hashes.
This requirement is considered a best practice until 31 March 2025, after which it will
be required and must be fully considered during a PCI DSS assessment. This requirement
will replace the bullet in Requirement 3.5.1 for one-way hashes once its effective date
is reached.

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
