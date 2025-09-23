---
x-trestle-global:
  profile:
    title: rhel9-pcidss_3-base
  sort-id: req-a3.02.02.01
---

# req-a3.2.2.1 - \[REPLACE_ME\] A3.2.2.1 Upon Completion Of A Change, All Relevant Pci Dss Requirements Must Be Verified On All New Or Changed Systems And Networks, And Documentation Must Be Updated As Applicable. Examples Of Pci Dss Requirements That Should Be Verified Include, But Are Not Limited To:

## Control Statement

* Network diagram is updated to reflect changes.
* Systems are configured per configuration standards, with all default
  passwords changed and unnecessary services disabled.
* Systems are protected with required controls.
  e.g., file-integrity monitoring (FIM), anti-virus, patches, audit logging.
* Verify that sensitive authentication data (SAD) is not stored
  and that all cardholder data (CHD) storage is documented and incorporated into
  data-retention policy and procedures
* New systems are included in the quarterly vulnerability scanning process.

PCI DSS Reference: Scope of PCI DSS Requirements; Requirement 1-12

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
