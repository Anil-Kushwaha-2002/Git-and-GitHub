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
  `git add .`
  `git commit -m "Initial commit"`
```
## 4. Push to GitHub
`git push origin main`


