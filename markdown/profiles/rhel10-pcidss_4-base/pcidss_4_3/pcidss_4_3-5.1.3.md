---
x-trestle-global:
  profile:
    title: rhel10-pcidss_4-base
  sort-id: pcidss_4_3-05.01.03
---

# pcidss_4_3-5.1.3 - \[REPLACE_ME\] If Disk-Level Or Partition-Level Encryption Is Used (Rather Than File-, Column-, Or Field--Level Database Encryption) To Render Pan Unreadable, It Is Managed.

## Control Statement

If disk-level or partition-level encryption is used (rather than file-, column-, or
field--level database encryption) to render PAN unreadable, it is managed as follows:
- Logical access is managed separately and independently of native operating system
authentication and access control mechanisms.
- Decryption keys are not associated with user accounts.
- Authentication factors (passwords, passphrases, or cryptographic keys) that allow
access to unencrypted data are stored securely.

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
