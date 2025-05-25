# Github Actions

- GitHub Actions is a CI/CD (Continuous Integration and Continuous Deployment) platform provided by GitHub.
- It allows developers to automate workflows directly within their repositories. 
- With GitHub Actions, you can define custom workflows using YAML files to automate tasks such as:
  - Building and testing code: Automatically run tests and builds when code is pushed or pull requests are created.
  - Deploying applications: Deploy code to production or staging environments.
  - Code analysis: Run linters, security scans, or other tools to ensure code quality.
  - Custom automation: Automate any task, such as sending notifications or managing issues.

## Table of Contents

- [Github Actions](#github-actions)
- [Pull Request Event](#pull-request-event)
- [Sample Github Actions yaml file](#sample-github-actions-yaml-file)

## Pull Request Event

What is the `pull_request` Event:
  - It tells GitHub Actions to run a workflow when someone creates a pull request that targets the `master` branch.
  - If someone opens a PR from `feature_branch` to `master`, the workflow will run even though the `feature_branch` is the one with changes.
  - This ensures we are testing the real future state of the repository, not just the feature branch alone.

What happened when the `pull_request` event triggers:
  - GitHub creates a temporary commit that merges `feature_branch` into `master`
  - It checks out that merge result and runs your workflow on it
  - Even if `feature_branch` works on its own, if it breaks master when merged, the CI will fail.

Why this Matters:
  - We are not testing just the code in the PR branch; we’re testing what the target branch (master) would look like if the PR were merged right now.
  - This catches merge conflicts, build failures, and integration issues early.
  - This temporary commit doesn’t get pushed to your repo; it's just created in GitHub’s CI environment.

Events involved in the process:
  - pull_request event: Runs workflow when a PR targets a specified branch
  - Temporary merge commit: GitHub simulates the result of merging the PR into the target branch master
  - Purpose: Ensures PR won’t break the target branch upon merge
  - Real-world value: Catches integration bugs, avoids broken master

## Sample Github Actions yaml file
- [cpp-build.yaml](.github/workflows/cpp-build.yaml)