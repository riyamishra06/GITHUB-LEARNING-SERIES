Main README.md
markdown# Git & GitHub Complete Learning Series 🚀

Welcome to the **Git & GitHub Complete Learning Series**! This 4-day guide is designed for absolute beginners to master version control and collaborative development using Git and GitHub. By the end, you'll be confident in managing projects and contributing to open source.

## Table of Contents
- [Day 1: Getting Started with Git & GitHub](#day-1)
- [Day 2: Basic Git Commands & Repositories](#day-2)
- [Day 3: Branching, Merging & GitHub Features](#day-3)
- [Day 4: Collaboration, Advanced Concepts & Best Practices](#day-4)

## How to Use This Series
- Follow the series over 4 days, spending 1-2 hours daily.
- Each day includes code examples with explanations.
- Practice the commands in your terminal to reinforce learning.
- Star ⭐ and fork 🍴 this repository to keep it handy!

## Prerequisites
- A computer (Windows, Mac, or Linux)
- Basic terminal/command-line knowledge
- A GitHub account

## Files
- [Day 1: Getting Started](day1.md)
- [Day 2: Basic Commands & Repositories](day2.md)
- [Day 3: Branching & GitHub Features](day3.md)
- [Day 4: Advanced Topics & Best Practices](day4.md)

## About
This series is created for beginners to learn Git & GitHub from scratch. If you find it helpful:
- ⭐ Star this repository
- 🍴 Fork it to your account
- 📢 Share it with others
- 🐛 Report issues or suggest improvements

**Happy Coding!** 💻✨

Day 1: Getting Started with Git & GitHub (day1.md)
markdown# Day 1: Getting Started with Git & GitHub 🚀

Welcome to Day 1 of the Git & GitHub Learning Series! Today, we'll cover the basics of Git and GitHub, and set up your environment to start version control.

## Table of Contents
1. [Introduction](#introduction)
2. [What is Git?](#what-is-git)
3. [What is GitHub?](#what-is-github)
4. [Installation & Setup](#installation--setup)

---

## Introduction

This series is designed for:
- Complete beginners to version control
- Developers wanting to improve Git skills
- Students preparing for interviews
- Anyone interested in open source contributions

By the end, you'll confidently use Git and GitHub for any project!

---

## What is Git?

**Git** is a distributed version control system that tracks changes in your code over time. Think of it as a "save system" for your projects that:
- Tracks every change
- Allows reverting to previous versions
- Enables team collaboration
- Prevents code conflicts and data loss

### Key Benefits:
- ✅ Track code changes
- ✅ Collaborate with others
- ✅ Backup your work
- ✅ Experiment safely
- ✅ Maintain project versions

---

## What is GitHub?

**GitHub** is a cloud-based platform that hosts Git repositories. It’s like Google Drive for code, with powerful collaboration tools:
- Stores Git repositories online
- Offers project management features
- Hosts websites for free
- Connects developers worldwide

### GitHub vs Git:
- **Git**: Tool on your computer
- **GitHub**: Platform on the internet

---

## Installation & Setup

Let’s get Git and GitHub set up on your computer!

### Step 1: Install Git

#### Windows:
1. Download Git from [git-scm.com](https://git-scm.com/)
2. Run the installer with default settings
3. Open Command Prompt or Git Bash

#### Mac:
```bash
# Using Homebrew
brew install git
Explanation: This command installs Git on Mac using Homebrew, a package manager. If you don’t have Homebrew, download Git from git-scm.com.
Linux (Ubuntu/Debian):
bashsudo apt update
sudo apt install git
Explanation: These commands update your package list and install Git on Ubuntu/Debian-based systems. sudo runs the command as an administrator.
Step 2: Initial Configuration
bash# Set your name
git config --global user.name "Your Name"

# Set your email
git config --global user.email "your.email@example.com"

# Check configuration
git config --list
Explanation:

git config --global user.name "Your Name": Sets your name for Git commits, visible in commit history.
git config --global user.email "your.email@example.com": Sets your email, which should match your GitHub email.
git config --list: Displays your Git configuration to verify settings.

Step 3: Create GitHub Account

Go to github.com
Sign up for a free account
Verify your email

Explanation: A:G): A GitHub account lets you store repositories online and collaborate with others. Email verification is required to use all features.

Practice Task

Install Git on your computer.
Configure your name and email using the git config commands.
Create a GitHub account and verify your email.
Open your terminal and run git --version to confirm Git is installed.