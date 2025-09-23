---
x-trestle-global:
  profile:
    title: rhel10-pcidss_3-base
  sort-id: req-04.01
---

# req-4.1 - \[REPLACE_ME\] 4.1 Use Strong Cryptography And Security Protocols (For Example, Tls, Ipsec, Ssh, Etc.) To Safeguard Sensitive Cardholder Data During Transmission Over Open, Public Networks, Including The Following:

## Control Statement

* Only trusted keys and certificates are accepted.
* The protocol in use only supports secure versions or configurations.
* The encryption strength is appropriate for the encryption methodology in
  use.

Note: SSL and early TLS are not considered strong cryptography and cannot
be used as a security control after June 30, 2016. Prior to this date, existing
implementations that use SSL and/or early TLS must have a formal Risk Mitigation
and Migration Plan in place.

Effective immediately, new implementations must not use SSL or early TLS.

POS POI terminals (and the SSL/TLS termination points to which they connect)
that can be verified as not being susceptible to any known exploits for SSL
and early TLS may continue using these as a security control after
June 30, 2016.

Examples of open, public networks include but are not limited to:
* The Internet
* Wireless technologies, including 802.11 and Bluetooth
* Cellular technologies, for example, Global System for Mobile
  communications (GSM), Code division multiple access (CDMA)
* General Packet Radio Service (GPRS)
* Satellite communications

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
