---
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-basic
  sort-id: sys-01.06.a3
---

# sys-1.6.a3 - \[REPLACE_ME\] Secure Use Of Containerised It Systems

## Control Statement

(1) In the case of containerised IT systems, consideration MUST be given to how containerisation affects the IT systems and applications operated, in particular the management and suitability of the applications. (2) Based on the protection needs of the applications, it MUST be checked whether the requirements for isolation and encapsulation of the containerised IT systems, virtual networks, and operated applications are sufficiently fulfilled. (3) The mechanisms of the operating system in question SHOULD be included in this check. (4) Since the host performs the function of a network component for virtual networks, the modules of the sub-layers NET.1 Networks and NET.3 Network Components MUST be considered accordingly. (5) Logical and overlay networks MUST also be considered and modelled. (6) Furthermore, the containerised IT systems used MUST meet the requirements at hand regarding availability and data throughput.(7) During operation, the performance and the state of the containerised IT systems SHOULD be monitored (health checks).

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
