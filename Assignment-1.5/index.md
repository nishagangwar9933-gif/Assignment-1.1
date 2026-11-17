# Assignment 1.5 — GitHub Essentials II

## Task Summary
Connect a local Git repository to a new public repository on GitHub, push the initial project files, add a new file (`README.md`) as a second commit, push the update, and verify the commit history online.

---

## Public GitHub Repository Link
* **Repository URL:** `https://github.com/<your-username>/<your-repo-name>` *(Replace with your actual public GitHub repository URL before submitting)*

---

## Record of Git & GitHub Commands Executed

### 1. Connect Local Repository to Remote GitHub Repository
```bash
# Navigate to your local project folder
cd web-development-practice

# Rename default branch to main (if not already named main)
git branch -M main

# Add the remote GitHub repository URL
git remote add origin [https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git

# Verify the remote connection
git remote -v