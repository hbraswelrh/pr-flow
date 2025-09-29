---
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_3_rhel9-standard
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
