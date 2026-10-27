SKILL LAB MODULE 5 — Git and GitHub Basics

The manual treats Module 5 as a Git/GitHub exercise, not as an HTML website.
Use CMD or Git Bash to perform the commands below.

1. Install Git for Windows; create a GitHub repository.
2. Set Git name and email (replace with your own):
   git config --global user.name "Your Name"
   git config --global user.email "you@example.com"
   git config --list
3. Create a folder, and run:
   git init
   git status
   git add .
   git commit -m "Initial commit"
4. Create and switch to a feature branch:
   git switch -c feature/add-task
5. Edit or add a file, then:
   git status
   git diff
   git add .
   git commit -m "Add task creation feature"
6. If your GitHub repo is ready, substitute its URL:
   git remote add origin https://github.com/YOUR_USER/YOUR_REPO.git
   git push -u origin feature/add-task
7. Open a pull request on GitHub and merge into main after review.
8. Useful commands discussed in manual:
   git restore FILE
   git rm --cached FILE
   git diff HEAD
   git stash
   git stash pop
   git reflog
   git branch -u origin/main

WARNING: git restore FILE discards uncommitted changes in that file.
Do not use any of these commands blindly in an existing repository.

The manual's Module 5 section discusses Git workflow, commits, branch management, syncing and reverting.
