# pr-flow


## Review the concept of branching

The `main` branch is the source of truth. The content merged to `main` must be reviewed and approved. 

### Create a new branch

**Scenario:** The version of PCI DSS has recently been updated. The existing content in the `main` branch is out-of-date, but you need to update the content to reflect the latest version of PCI DSS.

**Action:** Create a new branch from `main` and name it `pci-dss-v4.0.1`. The new branch will have the existing content from `main` and will be used to update the existing content of `pci-dss-v3.2.1`.

### Update the Markdown of an OSCAL Component Definition

## Opening a PR

To open a Pull Request, reference Step 2 of the `creme-brulee` GitHub course.

### Stage Changes

### Update the Markdown of an OSCAL Component Definition

### Validate with Documentation

## Reviewing a PR

### **Case 1:** The proposed content change _should_ be approved

If a user proposes content that is correct and should be merged to `main` there should be an explicit approval coupled with a comment "LGTM."

### **Case 2:** The proposed content change _should not_ be approved

If a user proposes content that is out-of-date or incorrect, the Pull Request should not be explicitly approved. The plan of action would be to update the PR with the corrected content via the "Request Changes" option on PR review. Otherwise, leaving a comment on the Pull Request with a suggestion or indication of changes needed.

## Resources

[ComplyTime Skills Discovery Course creme-brulee](https://github.com/complytime/creme-brulee)
[OSCAL Content Repository](https://github.com/ComplianceAsCode/oscal-content)