---
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_1_rhel9-standard
  sort-id: sys-01.01.a25
---

# sys-1.1.a25 - \[REPLACE_ME\] Controlled Decommissioning Of A Server

## Control Statement

(1) When decommissioning a server, it SHOULD be ensured that no important data that might
still be present on the storage media is lost and no sensitive data remains.
(2) There SHOULD be an overview of the data stored in each location on the server.
(3) Furthermore, it SHOULD be ensured that services offered by the server will be taken over
by another server when necessary.
(4) A checklist SHOULD be created that is to be completed when decommissioning a server.
(5) This checklist SHOULD at least include aspects related to backing up data, migrating
services, and subsequently deleting all data in a secure manner.

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
