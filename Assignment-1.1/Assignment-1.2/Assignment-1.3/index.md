# Assignment 1.3 — Terminal & Developer Workflow

## Task Summary
Create and manage a structured project directory (`web-development-practice`) exclusively using command-line interface (CLI) commands, practice directory navigation, renaming, and deletion, and launch the project in Visual Studio Code from the terminal.

---

## Record of Terminal Commands Used

### Option A: Windows (PowerShell)
```powershell
# 1. Create the main project folder and navigate into it
mkdir web-development-practice
cd web-development-practice

# 2. Create week-1, week-2, and week-3 folders inside it
mkdir week-1, week-2, week-3

# 3. Create an index.html file inside each folder
New-Item week-1\index.html, week-2\index.html, week-3\index.html -ItemType File

# 4. Practice navigating, renaming, and deleting a temporary folder
mkdir temp-folder
cd temp-folder
cd ..
Rename-Item temp-folder archive-folder
Remove-Item archive-folder

# 5. Verify the final folder structure
Get-ChildItem -Recurse

# 6. Open the project folder in VS Code from the terminal
code .