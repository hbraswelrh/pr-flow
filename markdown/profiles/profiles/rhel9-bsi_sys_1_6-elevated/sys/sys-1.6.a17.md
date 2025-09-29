---
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-elevated
  sort-id: sys-01.06.a17
---

# sys-1.6.a17 - \[REPLACE_ME\] Running Containers Without Privileges

## Control Statement

(1) A container runtime and any instantiated containers SHOULD only be executed by a non- privileged system account that does not have (and cannot gain) elevated rights to the container service or host operating system. (2) The container runtime SHOULD be encapsulated by additional measures, such as using the virtualisation extensions of CPUs. (3) If containers are to take over tasks of the host system in exceptional cases, privileges on the host system SHOULD be limited to the minimum necessary. (4)Exceptions SHOULD be adequately documented.

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
