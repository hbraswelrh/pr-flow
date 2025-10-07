# Navigating the OSCAL Markdown

The `creme-brulee` ComplyTime Skills Discovery course prepared you to _Communicate using Markdown and Git_.

The `markdown` folder builds on your understanding of Markdown and using a common language to express content.

The `markdown/component-definitions` folder includes several `complyscribe` generated OSCAL Component Definitions. Leverage the Markdown Component Definitions to open a Pull Request and practice with proposing changes to the content.

## Example using PCI-DSS

### PCI DSS v4.0.1 Requirement 8-3.6

> Path to Markdown Component Definition: `markdown/component-definitions/PCIDSS-Component/software-comp/rhel9-pcidss_4-base/pcidss_4_8/pcidss_4_8-3.6.md`

When looking at the Markdown format the `<! text !>` are comments that guide you through what parts of the Component Definition can be edited.

Once making changes, commit those changes using an impactful commit message.

> Example commit message: `feat: update control implementation description`

From there, open a Pull Request to propose your changes to the `main` branch.

## Important Notes

When editing the OSCAL Markdown Component Definitions **DO NOT** delete or update the `\[REPLACE_ME\]`. This is equivalent to a control description variable. 

The Markdown Component Definitions can be updated, but are used to translate back to OSCAL format. Therefore, the `\[REPLACE_ME\]` should simply be ignored when editing the Component Definitions. 
