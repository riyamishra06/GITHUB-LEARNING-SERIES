
# Day 3: Branching, Merging & GitHub Features 🚀

Welcome to Day 3! Today, we’ll learn how to work with branches, merge changes, and explore GitHub’s collaboration tools.

## Table of Contents
1. [Branching & Merging](#branching--merging)
2. [GitHub Features](#github-features)

## Branching & Merging

### What are Branches?
Branches let you work on different features simultaneously without affecting the main code.

### Branch Commands

#### Create and Switch Branches
# Create new branch
git branch feature-name

# Switch to branch
git checkout feature-name

# Create and switch in one command
git checkout -b feature-name

# Modern way (Git 2.23+)
git switch -c feature-name
Explanation:

git branch feature-name: Creates a new branch called feature-name.
git checkout feature-name: Switches to the specified branch.
git checkout -b feature-name: Combines branch creation and switching.
git switch -c feature-name: A modern alternative for creating and switching branches.

List and Delete Branches
bash# List all branches
git branch

# List remote branches
git branch -r

# Delete branch
git branch -d feature-name

# Force delete branch
git branch -D feature-name
Explanation:

git branch: Lists local branches, with the current branch marked by *.
git branch -r: Lists remote branches.
git branch -d feature-name: Deletes a merged branch.
git branch -D feature-name: Force-deletes an unmerged branch.

Merging Branches
bash# Switch to main branch
git checkout main

# Merge feature branch
git merge feature-name
Explanation:

Switches to the main branch and merges changes from feature-name.
Types of merges:

Fast-forward: Linear history when no conflicts exist.
Three-way: Creates a merge commit for complex changes.
Squash: Combines all commits into one.



Practical Example
bash# Create a new feature
git checkout -b add-navigation
echo "<nav>Navigation</nav>" > nav.html
git add nav.html
git commit -m "Add navigation component"

# Switch back to main
git checkout main

# Merge the feature
git merge add-navigation

# Delete the feature branch
git branch -d add-navigation
Explanation:

Creates a branch add-navigation, adds nav.html, and commits.
Switches to main, merges add-navigation, and deletes the branch.
This workflow isolates feature development and integrates it cleanly.


GitHub Features
1. Issues
Track bugs, features, or tasks:

Create descriptive titles and details.
Use labels (e.g., bug, enhancement) and milestones.
Assign to team members or link to pull requests.

2. Pull Requests (PRs)
Propose and review changes:

Fork → Clone → Branch → Commit → Push → Create PR
Review code, comment, and approve.
Integrate automated tests or merge strategies.

3. GitHub Actions
Automate workflows:

Run tests on every push.
Deploy code automatically.
Format code or manage dependencies.

4. Project Boards
Organize tasks with Kanban boards:

Columns: To Do, In Progress, Done
Link issues and PRs to track progress.

5. GitHub Pages
Host websites for free:
bash# Enable GitHub Pages
# Go to Settings → Pages → Source: main branch
# Site URL: https://username.github.io/repository-name
Explanation: GitHub Pages hosts static websites from your repository. Enable it in the repository settings, selecting the main branch as the source.

Practice Task

Create a branch, add a file, and commit changes.
Merge the branch into main and delete it.
Create a GitHub repository and enable GitHub Pages.
Explore the Issues and Projects tabs on GitHub.
Push your branch to GitHub and create a Pull Request.