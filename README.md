# gh-label-sync

🏷 Manage and sync GitHub labels in one place.

This repository uses [action-label-syncer](https://github.com/micnncim/action-label-syncer) to sync GitHub labels.

## Getting started

1. Start by creating a repository using this template on GitHub.
2. Save your configured labels as YAML manifest file in the `./labels` directory ([Example](https://github.com/robingenz/.gh-label-sync/blob/main/labels/default.yml)).
3. To operate on other repositories, you have to store a personal access token ([GitHub Settings](https://github.com/settings/tokens)) with the scope `repo` as an  Actions secret named `GH_PAT`.

## Sync labels

Go to `Actions -> Sync labels -> Run workflow` and select the `repository` and `labels file name`.
Run the workflow.
