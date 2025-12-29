# Git & GitHub Lab Report

## Screenshots
The following screenshots are included to show progress at key checkpoints:
- Initial repository creation and first commit (`git log --oneline`)
- Feature branch creation and commits
- Pull Request creation and merge on GitHub
- Final repository state on GitHub

## Reflection

### What was challenging?
The most challenging part was configuring GitHub connectivity from WSL, especially resolving DNS issues that prevented pushing to the remote repository. Understanding how local Git repositories interact with remote GitHub repositories also required careful attention.

### How does Git help in DevOps teams?
Git enables collaboration by allowing multiple developers to work on features independently using branches. Pull Requests provide a structured way to review changes before merging, reducing errors and improving code quality. Git also provides a clear history of changes, which is essential for auditing, debugging, and continuous integration in DevOps workflows.

## Issues Faced and How They Were Resolved
- **Issue:** Unable to push to GitHub due to DNS resolution errors.
  **Resolution:** Fixed WSL DNS configuration by updating `/etc/resolv.conf`, disabling auto-generation in `/etc/wsl.conf`, and restarting WSL.
- **Issue:** Confusion about Pull Request merge visibility.
  **Resolution:** Learned that the merge button appears only after creating the Pull Request and opening the PR conversation page.

