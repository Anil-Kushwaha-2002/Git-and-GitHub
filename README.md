# Git and GitHub

# 🔍 What is Git?
Git is a distributed version control system that tracks changes in your codebase. It helps you:
- Keep a history of code changes
- Collaborate with others
- Create different branches for features
- Revert or fix bugs with ease
- 💡 Version Control = A system that records changes to files over time.

# 🐙 What is GitHub?
GitHub is a cloud-based platform built around Git. It hosts your Git repositories and adds collaboration features like:
- Pull requests
- Issues and bug tracking
- Actions (CI/CD)
- Project boards
- 🧠 Think of GitHub as a social platform for Git repositories.

# ⚙️ Basic Git Workflow
`[Working Directory] ➜ [Staging Area] ➜ [Local Repository] ➜ [Remote Repository]`

| Stage             | Command Example           | Description                                    |
| ----------------- | ------------------------- | ---------------------------------------------- |
| Working Directory | `code file.py`            | You create or edit files                       |
| Staging Area      | `git add file.py`         | Prepares files to be committed                 |
| Local Repository  | `git commit -m "message"` | Commits the changes with a message             |
| Remote Repository | `git push origin main`    | Uploads changes to GitHub (or any remote repo) |


# 🌐 Git & GitHub Notes
🧱 Initial Setup (Configuration)
- Sets your global Git identity.  (--global applies these settings to all repositories on your system.)
```
git config --global user.name "Anil Kushwaha"
git config --global user.email "your-email@example.com"
git config --global user.[ _ _ _ ]
```
💻 Open Project in VS Code
- Opens the current folder in Visual Studio Code
`code .`

🔗 Clone Repository (from GitHub to your local system)
`git clone <repository-URL>`

📦 Initialize Git in a New Project
- Creates a new Git repository locally by adding a hidden .git folder.
`git init`



# 📘 Common Git Commands (with Purpose)
| Task                     | Command                                                |
| ------------------------ | ------------------------------------------------------ |
| Initialize Git repo      | `git init`                                             |
| Check repo status        | `git status`                                           |
| Add file to staging      | `git add filename` or `git add .`                      |
| Commit with message      | `git commit -m "message"`                              |
| See commit history       | `git log` or `git log --oneline`                       |
| Create a branch          | `git branch branch_name`                               |
| Switch to branch         | `git checkout branch_name` or `git switch branch_name` |
| Create and switch branch | `git checkout -b new_branch`                           |
| Merge branches           | `git merge branch_name`                                |
| View branches            | `git branch`                                           |
| Delete branch            | `git branch -d branch_name`                            |


# 🌐 GitHub Workflow Example
## 1. Create Repo on GitHub
## 2. Clone the Repo to Local Machine
```
git clone https://github.com/yourname/repo.git
cd repo
```
## 3. Work Locally
- Edit files
- Add & commit changes:
```
git add .
git commit -m "Initial commit"
```
## 4. Push to GitHub
```
git push origin main
```
## 5. Create Branch for New Feature
```
git checkout -b new-feature
```
## 6. Push New Branch
```
git push -u origin new-feature
```
## 7. Create Pull Request (PR) on GitHub
- PR = Propose changes to be merged into main
## 8. Merge PR after review

# 🔀 Branching Explained
Why Branch?
- Work on new features or fixes without affecting the main codebase.
- Example:
```
git checkout -b login-feature
# Do your work
git add .
git commit -m "Add login form"
git checkout main
git merge login-feature
```


