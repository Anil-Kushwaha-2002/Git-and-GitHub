**✅ BASIC Git Commands (Daily Usage)**

Purpose	Command	Notes

Initialize Git in a directory	git init	Creates .git folder

Check status	git status	See tracked/untracked/staged files

Add file to staging	git add file.txt	Add single file

Add all changes to staging	git add . or git add -A	Adds everything

Commit changes	git commit -m "Message"	Save snapshot

View commit history	git log / git log --oneline	Shows commit list

Check current branch	git branch	Shows local branches

Create a new branch	git branch feature-1	Only creates

Switch branch	git checkout feature-1 / git switch feature-1	Moves to that branch

Create + switch branch	git checkout -b new-branch	Shortcut

View differences	git diff	Shows unstaged changes

Push changes to GitHub	git push origin main	Uploads to remote

Pull latest from GitHub	git pull origin main	Downloads latest

Clone repository	git clone https://github.com/user/repo.git	Copy from GitHub



**🛠️ INTERMEDIATE Git Commands (Team Workflow)**

Purpose	Command	Notes

View remote(s)	git remote -v	See URLs for origin

Add a remote repository	git remote add origin <url>	Link local to remote

Rename branch	git branch -m new-name	Rename local branch

Delete local branch	git branch -d branch-name	Only if merged

Delete remote branch	git push origin --delete branch-name	Use with caution

Stage part of a file	git add -p	Choose what to stage

Unstage a file	git reset HEAD file.txt	Keeps changes

Amend last commit	git commit --amend	Change message or add files

Show last commit	git show	View last commit details

Reset file to last commit	git checkout -- file.txt	Discards local changes

Revert a commit (undo safely)	git revert <commit-id>	Adds reverse commit

Create tag	git tag v1.0	Useful for releases

Push tags	git push origin --tags	Push all tags

Fetch without merging	git fetch	Update local info

Set upstream branch	git push -u origin branch-name	Links local to remote



**🚀 ADVANCED Git Commands (Power Use)**

Purpose	Command	Notes

Interactive rebase	git rebase -i HEAD~3	Edit last 3 commits

Rebase a branch	git rebase main	Clean history before merge

Squash commits	Use rebase -i and choose squash	Combines commits

Stash current changes	git stash	Save work temporarily

Apply stashed changes	git stash apply	Bring back stashed code

List all stashes	git stash list	View stash stack

Delete stash	git stash drop / git stash clear	Remove stash

Remove file from Git (keep in folder)	git rm --cached file.txt	Untrack file

Remove file completely	git rm file.txt	Delete from disk and Git

Clean untracked files	git clean -f	Deletes untracked files

View file history	git log file.txt	Shows history of a file

Blame: who edited what	git blame file.txt	Shows line-by-line author

Check config	git config --list	View all configs

Set global username/email	git config --global user.name "Anil"

git config --global user.email "you@example.com"	Set identity

Git alias	git config --global alias.co checkout	Custom shortcuts



**🐙 GitHub-Specific Commands and Usage**

Task	Tool / Command

Create repo on GitHub	Web UI

Clone repo	git clone <URL>

Fork a repo	GitHub Web UI

Create pull request	GitHub Web UI

Review code, assign reviewers	GitHub Web UI

Merge pull request	GitHub Web UI

Create GitHub Action workflow	.github/workflows/\*.yml

Use Issues for bugs/features	GitHub Web UI

Use Projects for kanban-style planning	GitHub Web UI

Enable branch protection	GitHub Repo Settings

Add collaborators	GitHub → Repo → Settings → Collaborators

