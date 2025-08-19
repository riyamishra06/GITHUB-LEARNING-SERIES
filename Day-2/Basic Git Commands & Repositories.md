
# Day 2: Basic Git Commands & Repositories 🚀

Welcome to Day 2! Today, we’ll learn essential Git commands and how to work with local and remote repositories.

## Table of Contents
1. [Basic Git Commands](#basic-git-commands)
2. [Working with Repositories](#working-with-repositories)

## Basic Git Commands

### The Git Workflow
Working Directory → Staging Area → Repository
textWorking Directory: Your project folder with files.
Staging Area: Files you’re preparing to commit.
Repository: Where committed changes are stored.

### Essential Commands

#### 1. Initialize a Repository
git init
Explanation: Creates a new Git repository in your current folder, initializing a .git directory to track changes.
2. Check Status
bashgit status
Explanation: Shows modified, staged, or untracked files in your working directory, helping you track changes.
3. Add Files to Staging
bashgit add filename.txt
git add .
git add *.js
Explanation:

git add filename.txt: Stages a specific file.
git add .: Stages all modified and new files.
git add *.js: Stages all JavaScript files using a wildcard.

4. Commit Changes
bashgit commit -m "Your commit message"
Explanation: Saves staged changes to the repository with a descriptive message explaining the changes.
5. View Commit History
bashgit log
git log --oneline
Explanation:

git log: Shows detailed commit history (author, date, message).
git log --oneline: Displays a compact, one-line summary of commits.

6. Check Differences
bashgit diff
git diff --staged
Explanation:

git diff: Shows unstaged changes in your working directory.
git diff --staged: Shows changes staged for the next commit.

Example Workflow
bash# Create a new project
mkdir my-project
cd my-project
git init

# Create a file
echo "Hello World" > index.html

# Track and commit
git add index.html
git commit -m "Add index.html file"

# Make changes
echo "<h1>Hello World</h1>" > index.html

# Commit changes
git add index.html
git commit -m "Update index.html with HTML tags"
Explanation:

Initializes a repository, creates index.html, stages, and commits it.
Modifies index.html with HTML tags, then stages and commits the changes.
Each commit creates a snapshot of the project at that point.


Working with Repositories
Local vs Remote Repositories

Local Repository: On your computer, managed by Git.
Remote Repository: On GitHub, for collaboration and backup.

# Connecting Local to Remote
Method 1: Clone a GitHub Repository
bashgit clone https://github.com/username/repository-name.git
cd repository-name
Explanation: Downloads a remote repository to your computer, including all files and history, and sets up the remote connection.
Method 2: Push Local Repository to GitHub
bash# Add remote origin
git remote add origin https://github.com/username/repository-name.git

# Push to GitHub
git push -u origin main
Explanation:

git remote add origin ...: Links your local repository to a GitHub repository.
git push -u origin main: Pushes your local main branch to GitHub and sets it as the default branch.

Common Remote Commands
bash# Check remote repositories
git remote -v

# Fetch latest changes
git fetch origin

# Pull latest changes
git pull origin main

# Push your changes
git push origin main
Explanation:

git remote -v: Lists remote connections (URLs).
git fetch origin: Downloads updates from GitHub without merging.
git pull origin main: Downloads and merges changes from the main branch.
git push origin main: Uploads your local commits to GitHub.


Practice Task

Create a local repository using git init.
Add a file, stage it, and commit it with a message.
Create a new repository on GitHub.
Connect your local repository to GitHub and push your changes.
Run git status, git log --oneline, and git diff to explore your repository.