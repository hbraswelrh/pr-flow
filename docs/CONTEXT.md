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
                "uuid": "bbdcd591-aac1-4343-9d2b-3f8beb3a9437",
                "control-id": "pcidss_4_8-3.6",
                "description": "This requirement is not intended to apply to:\n- User accounts on point-of-sale terminals that have access to only one card number at a\ntime to facilitate a single transaction (such as IDs used by cashiers on point-of-sale\nterminals).\n- Application or system accounts, which are governed by requirements in section 8.6.",
                "props": [
                  {
                    "name": "implementation-status",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "implemented"
                  },
                  {
                    "name": "Rule_Id",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "accounts_password_pam_dcredit"
                  },
                  {
                    "name": "Rule_Id",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "accounts_password_pam_lcredit"
                  },
                  {
                    "name": "Rule_Id",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "accounts_password_pam_minlen"
                  }
                ]
              },

```

```json

  {
                "uuid": "b0ea6309-17e4-47aa-b0df-5707d6df0891",
                "control-id": "pcidss_4_8-3.6",
                "description": "This requirement is not intended to apply to:\n- User accounts on point-of-sale terminals that have access to only one card number at a\ntime to facilitate a single transaction (such as IDs used by cashiers on point-of-sale\nterminals).\n- Application or system accounts, which are governed by requirements in section 8.6.",
                "props": [
                  {
                    "name": "implementation-status",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "implemented"
                  },
                  {
                    "name": "Rule_Id",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "accounts_password_pam_dcredit"
                  },
                  {
                    "name": "Rule_Id",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "accounts_password_pam_lcredit"
                  },
                  {
                    "name": "Rule_Id",
                    "ns": "https://oscal-compass.github.io/compliance-trestle/schemas/oscal/cd",
                    "value": "accounts_password_pam_minlen"
                  }
                ]
              },
```

Rules in Markdown Component Definition
