# Context for PCI-DSS Example 


## Where to find the Markdown Component Definition

[`./markdown/component-definitions/PCIDSS-Component/software-comp/rhel9-pcidss_4-base/pcidss_4_8/pcidss_4_8-3.6.md`](https://github.com/hbraswelrh/pr-flow/blob/main/markdown/component-definitions/PCIDSS-Component/software-comp/rhel9-pcidss_4-base/pcidss_4_8/pcidss_4_8-3.6.md)

#### PCI-DSS Requirement

PCI-DSS Req 8.3.6 [PDF](https://www.commerce.uwo.ca/pdf/PCI-DSS-v4_0.pdf)



#### Example ComplianceAsCode/content

The id 8.3.6 is referenced in the ComplianceAsCode/content control file for PCIDSS. 

```yaml

 - id: 8.3.6
            title: If passwords/passphrases are used as authentication factors to meet Requirement 8.3.1,
                they meet the minimum level of complexity.
            description: |-
                - A minimum length of 12 characters (or IF the system does not support 12 characters, a
                minimum length of eight characters).
                - Contain both numeric and alphabetic characters.
                A guessed password/passphrase cannot be verified by either an online or offline brute
                force attack.
            levels:
                - base
            status: automated
            notes: |-
                This requirement is not intended to apply to:
                - User accounts on point-of-sale terminals that have access to only one card number at a
                time to facilitate a single transaction (such as IDs used by cashiers on point-of-sale
                terminals).
                - Application or system accounts, which are governed by requirements in section 8.6.
            rules:
                - var_password_pam_dcredit=1
                - var_password_pam_lcredit=1
                - var_password_pam_minlen=12
                - accounts_password_pam_dcredit
                - accounts_password_pam_lcredit
                - accounts_password_pam_minlen
                - cracklib_accounts_password_pam_dcredit
                - cracklib_accounts_password_pam_lcredit
                - cracklib_accounts_password_pam_minlen
            related_rules:
                - var_password_pam_ocredit=1
                - var_password_pam_ucredit=1
                - accounts_password_pam_ucredit
                - cracklib_accounts_password_pam_ocredit
                - cracklib_accounts_password_pam_ucredit


```

#### Example OSCAL Component Definition 

```json
     {
                "uuid": "16f5919d-c282-4379-93cb-cf386cdaaf3f",
                "control-id": "pcidss_4_8-6.3",
                "description": "Related to requirements 8.3.6 and 8.3.9.",
                "props": [
                  {
                    "name": "implementation-status",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "implemented"
                  }
                ]
              },

```

```json

      {
                "uuid": "8ce094c3-6a88-4ddd-b0b7-315001dc81cd",
                "control-id": "pcidss_4_8-6.3",
                "description": "Related to requirements 8.3.6 and 8.3.9.",
                "props": [
                  {
                    "name": "implementation-status",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "implemented" # Change this to "not-implemented"
                  }
                ]
              },
```