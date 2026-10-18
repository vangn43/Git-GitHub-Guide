# Understanding Git Branches and Pull Requests

## Introduction
This guide explains how branches and pull requests work in Git and GitHub. These features help developers make changes to their project without affecting the main version.

## What is a Git Branch?
A branch is a separate version of a project where developers can make changes without affecting the main branch. This is helpful when testing new features or fixing problems.

## Why Are Branches Useful?
Branches are useful because they allow developers to work on different parts of a project. If something goes wrong, the main version of the project will not be affected until the changes are merged.

## How to Create a Branch
1. Open your project in VS Code.
2. Open the terminal.
3. Type `git switch main` to switch to the main branch.
4. Type `git pull origin main` to get the latest changes.
5. Type `git switch -c feature/example` to create a new branch.
6. Make changes to your files on the new branch.

## What is a Pull Request?
A pull request is a way to suggest changes from one branch to another. It allows developers to review the changes before adding them to the main branch.

## How to Create a Pull Request
1. Push your feature branch to GitHub.
2. Open your repository on GitHub.
3. Click the Pull Requests tab.
4. Click New pull request.
5. Select main as the base branch and your feature branch as the compare branch.
6. Add  a title and description.
7. Click Create pull request.

## How to Merge a Pull Request
1. Open the pull request on GitHub.
2. Review the changes under Files changed.
3. Make sure thatt there are no merge conflicts.
4. Click Merge pull request.
5. Click Confirm merge.
6. Delete the feature branch when finished.