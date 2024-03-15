# *Git Basics:*

## Initialize a new Git repository:
```bash
git init
```
*Example:* Navigate to your project folder and run `git init` to initialize a new Git repository.

## Clone a repository:
```bash
git clone <repository-url>
```
*Example:* `git clone https://github.com/example/repo.git` to clone a remote repository.

## Add changes to the staging area / Add file in the staging area:
```bash
git add <file_name>
git add .
```
*Example:* `git add index.html` to stage a specific file, or `git add .` to stage all changes.

## Commit changes:
```bash
git commit -m "commit message"
```
*Example:* `git commit -m "Initial commit"` to commit staged changes with a message.

## Check the status of the working directory:
```bash
git status
```
*Example:* `git status` to see the current status of your working directory.

## View commit history:
```bash
git log
```
*Example:* `git log` to display a log of all commits.

## Undo the last commit:
```bash
git reset HEAD~1
```
*Example:* `git reset HEAD~1` to undo the last commit while keeping changes in the working directory.

## Undo changes in the working directory:
```bash
git checkout -- <file>
```
*Example:* `git checkout -- index.html` to discard changes in the working directory.
