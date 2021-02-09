# Introduction to Git

**git init** - turns any directory into a Git repository.

**git status** - shows the current state of your Git working directory and staging area.
**git commit** - creates a commit, which is like a snapshot of your repository. These commits are snapshots of your entire repository at specific times.

**git commit -m "descriptive commit message"**: This starts the commit process, and allows you to include the commit message at the same time.

**git add <path>**- stages a specific directory or file
**git add** - stages all files in the entire repository
**git add -N**
**git add** - adds new or changed files in your working directory to the Git staging area
**git push** -uploads all local branch commits to the remote.
**git push -u origin [branch]** - useful when pushing a new branch, this creates an upstream tracking branch with a lasting relationship to your local branch
**git remote** -  manages the set of remotes that you are tracking with your local repository

*Steps to update my repository, when I made some changes to my code:*
1. git add <path> or git add .
2. git commit -m "title"
3. git push