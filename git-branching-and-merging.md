# **Branching and Merging:**

## Create a new branch:
```bash
git branch <branch-name>
```
*Example:* `git branch feature-branch` to create a new branch named "feature-branch."

## Switch to a branch:
```bash
git checkout <branch-name>
```
*Example:* `git checkout feature-branch` to switch to the "feature-branch."

## Create and switch to a new branch:
```bash
git checkout -b <new-branch-name>
```
*Example:* `git checkout -b new-feature` to create and switch to a new branch named "new-feature."

## Merge changes from one branch to another:
```bash
git merge <branch-name>
```
*Example:* `git merge feature-branch` to merge changes from "feature-branch" into the current branch.

## Rename a branch:
```bash
git branch -m <new-branch-name>
```
*Example:* `git branch -m new-name` to rename the current branch to "new-name."

## Delete a branch:
```bash
git branch -d <branch-name>
```
*Example:* `git branch -d feature-branch` to delete the "feature-branch."

## Compare changes between branches:
```bash
git diff <branch-name>
```
*Example:* `git diff feature-branch` to compare changes between the current branch and "feature-branch."
