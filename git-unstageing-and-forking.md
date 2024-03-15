# Unstage changes:

### Undoing Changes:
```bash
git reset <file>
```
*Example:* `git reset index.html` to unstage changes in the "index.html" file.

### Undo last commit:
```bash
git reset HEAD~1
```
*Example:* `git reset HEAD~1` to undo the last commit while keeping changes in the working directory.

### Undo committed changes (soft):
```bash
git reset commit-hash
```
*Example:* `git reset abc123` to undo committed changes up to the specified commit.

### Undo committed changes (hard):
```bash
git reset --hard commit-hash
```
*Example:* `git reset --hard abc123` to discard changes and reset to the specified commit.

### **Git Log:**

- **View commit history:**
  ```bash
  git log
  ```
  *Example:* `git log` to display a log of all commits.

# **Forking:**

- **Fork a repository on GitHub:**
  - Click on the "Fork" button on the GitHub repository page.

*Example:* Visit a repository on GitHub and click the "Fork" button.

### **Additional Notes:**

- `HEAD` is a reference to the last commit in the currently checked-out branch.
