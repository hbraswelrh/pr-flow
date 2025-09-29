---
x-trestle-global:
  profile:
    title: rhel10-pcidss_4-base
  sort-id: pcidss_4_4-02.02
---

# pcidss_4_4-2.2 - \[REPLACE_ME\] Pan Is Secured With Strong Cryptography Whenever It Is Sent Via End-User Messaging Technologies.

## Control Statement

Cleartext PAN cannot be read or intercepted from transmissions using end-user messaging
technologies. This requirement also applies if a customer, or other third-party, requests
that PAN is sent to them via end-user messaging technologies. There could be occurrences
where an entity receives unsolicited cardholder data via an insecure communication channel
that was not intended for transmissions of sensitive data. In this situation, the entity
can choose to either include the channel in the scope of their CDE and secure it according
to PCI DSS or delete the cardholder data and implement measures to prevent the channel
from being used for cardholder data.

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
