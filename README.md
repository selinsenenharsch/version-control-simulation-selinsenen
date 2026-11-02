 Version Control Simulation SBA 1

A practice project focused on mastering foundational Git workflows, feature branching, and merge conflict resolution.

## Project Overview
This repository simulates a collaborative coding environment using a simple HTML project (`index.html`). The objective was to practice standard version control practices—such as initializing a repository, managing distinct feature branches, merging updates, and manually resolving merge conflicts in VS Code.

## Workflow & Steps Followed

1. **Repository Setup (`main`)**
   * Initialized a local Git repository (`git init`).
   * Created a baseline `index.html` file with HTML boilerplate structure and performed an initial commit.

2. **Feature Branching (`feature/header`)**
   * Created and switched to a dedicated `feature/header` branch.
   * Added a `<header>` section to `index.html` and committed the changes.

3. **Branching & Merge Conflict Simulation (`feature/footer`)**
   * Created a `feature/footer` branch from `main` to add a `<footer>` section.
   * Independently added competing footer/header changes on the `feature/header` branch to intentionally trigger a merge conflict.
   * Switched back to `main`, merged `feature/footer`, and then merged `feature/header`.
   * Resolved the resulting merge conflicts directly in VS Code with applying changes and finalized the merge with a commit.

4. **Remote Deployment**
   * Linked the local repository to a remote repository on GitHub and pushed up the final code.
