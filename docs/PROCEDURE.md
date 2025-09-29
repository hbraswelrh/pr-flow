# Procedure for ComplyTime Training

## Create a new branch

### Branching Semantics 

The branching semantics that align with this source should be followed when creating a branch that will be used to open a Pull Request.

**Ex:** You update a HIPAA Component Definition and want to Open a Pull Request to ensure the source of truth includes your reasoning. You create a new branch `feat/HIPAA-X.x.xx` and the reviewers are automatically aware that you are proposing an update to the HIPAA Component Definition.

**`feat`:** new feature for the user (i.e. new control implementation description)

**`fix`:** bug fix for the user (i.e. incorrect spelling for control implementation or wrong version)

**`style`:** formatting, missing semi colons etc.


## Edit a Component Definition in Markdown 

Edit a component definition for NAME-changed-item on your branch `feat/NAME-changed-item`. Common changes include updating the control implementation description, addressing evidence that should be included as verbiage on the description.  

### Control Implementation

## Open a Pull Request

After making changes to the Markdown Component Definition, the yellow banner should pop-up that indicates `feat/NAME-changed-item` recently pushed changes." Once this bannear appears, click Compare & Pull Request. This action will have a pre-populated template that allows you to update the context of your changes.   

### Assign Reviewers for PR 

> Assign reviewers in the top right corner "Reviewers." Since the exercise will be completed in pairs, it is best to request a review from a separate group. 

## Review a Pull Request

### Approval of a Pull Request

Reviewing the Pull Request requires a few prerequisites. 

```text
1. Are you familiar with the content that was changed or added?
2. Have you reviewed the Deliverables in the GitHub Issue?
3. Comfortability in the GitHub UI.
```

Review the Pull Request contents that were made on `feat/NAME-changed-item` and provide feedback in the comments. There will be an issue attached to the pull request body that can be referenced for full context on the deliverables of the exercise. Review the issue for more context and proceed with your review. 

If the Pull Request satisfies the "Deliverables" section of the GitHub issue, the Pull Request can be Approved. To approve, review each changed file in the "Files Changed" section. Then, click "Review Changes" which will allow you to check each box associated with a changed file.

Choose the Approve Changes option and comment "LGTM." (looks good to me). Feel free to add any context to the approval comment that would support your understanding of the review content.

### Rejection of a Pull Request

### Requesting Changes on a Pull Request

In the case of changes being made to a Component Definition that are inaccurate, grammatically incorrect, or anything that could be potentially threatening to the credibility of the source, you must request changes on the Pull Request. 

#### How to Request Changes

To request changes, navigate to the "Files Changed" tab on the Pull Request body and Click "Start a Review." 

From there, you can change specific lines in the changed file if the errors are minimal. Otherwise, leaving a review comment and selecting "Request Changes" will require the user to perform a self-review and update any inaccuracies in their Pull Request. 

#### Re-review Required after Requesting Changes

Once the "Request Changes" review is made, the user that opened the Pull Request must make those changes or re-evaluate their approach and commit those fixes. Only then will the review be able to "re-review" the changes made to the Pull Request. 

If the Pull Request abides by the Deliverables documented in the GitHub Issue that is attached to the PR body, then the contents can be explicitly approved and will again require the "Approve Changes" indication and the "LGTM." comment.
