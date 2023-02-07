This GitHub action automatically merges pull requests from any feature branches to the main branch and then to the qa branch upon approval. The action is triggered when the pull request is approved and has the label QaMerge. The status of the merge to the qa branch will be indicated by adding the label QASuccess if the merge was successful, or QAFailed if the merge was unsuccessful. The status update will be communicated to a Slack channel through a webhook.

To use this action, simply create a pull request from a feature branch to the main branch and add the label QaMerge. Upon approval of the pull request, the action will automatically merge the feature branch to the main branch and then to the qa branch. The merge to the main branch is pending and must be done manually. The status update of the merge to the qa branch will be posted to the designated Slack channel for monitoring and further action.





# How to Use

## GitHub Action for Automatic Merging to QA Branch
This GitHub action automates the process of merging pull requests from any feature branches to the qa branch upon approval.

## How to Use
- Create a pull request from a feature branch
- Add the label QaMerge to the pull request
- Upon approval, the action will automatically merge the pull request to the qa branch
- If you wish to merge to the main branch, you will need to do this manually.
## Notifications
- The status of the merge will be indicated by adding the label QASuccess if the merge was successful, or QAFailed if the merge was unsuccessful.
- The status update will be communicated to a Slack channel through a webhook for monitoring and further action.

Note: The pull request must be generated from a feature branch to the main branch.
