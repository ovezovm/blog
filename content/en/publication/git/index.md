---
title: Version Control. Git.
subtitle: In this post, I will share some information on the topic "Version Control. Git."

# Summary for listings and search engines
summary: Version Control Git.

# Link this post with a project
projects: []

# Date published
date: '2023-03-16T00:00:00Z'

# Date updated
lastmod: '2023-03-16T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

authors:
  - admin

tags:
  - Academic

categories:
  - GIT
  
---

## Version Control System

**Version Control System** is a tool used to track, apply, and manage changes in code. It can also simply be called version control.

Version control systems help developers save the changes made to a file at different stages so that both they and their colleagues can view them later.

There are three types of version control systems:

- Local version control systems \
- Centralized version control systems \
- Distributed version control systems.

## What is Git?

**Git** is a free and open-source distributed version control system that can be used to track changes in your files. With Git, you can work on all types and sizes of projects.

Using Git, you can add changes to your code and commit (or save) them when necessary. This means you can always revert to previous changes. Git works hand in hand with GitHub.

## What is GitHub?

**GitHub** is a web interface where you can store your Git repositories and efficiently track and manage your changes. It allows different developers to access the code of a single project. You can make your own changes to a project simultaneously with other developers.

For example, if you make a mistake while making changes, you can easily return to the previous stage where no error occurred.

## Git Principles

When working with Git, developers usually follow three principles:

1. Commit regularly — save changes in Git frequently. This will allow for a more detailed version history and help identify errors quickly.

2. Create new branches. They make it easy to manage changes, especially parallel ones. It's better to create a new branch than to mess up the old one.

3. Clearly and concisely describe commits. The code changes sent to Git must contain explanations and comments on the added edits and improvements. This greatly simplifies collaboration and helps in understanding old code.

## Main Git Commands

Git version control is a command-line program that represents a distributed version control system, meaning each developer has their own copy of the repository with the full history of changes. Let's consider the main commands for working with Git.

There are several basic Git commands that every developer should know:

- `git config` - this command is used to set the username, email address, and user branch to determine who made the changes while working on the project. \

- `git init` - this command is used to initialize Git in your project to track changes made to the project. \

- `git remote add origin` - sets the origin for our repository, where we store our code in the cloud. \

- `git add` - this command adds your file to the staging area. \

- `git commit` - this command commits any file that was added using the `git add` command, as well as all files in the staging area. \

- `git clone` - this command is used to copy an existing repository from one place to another. \

- `git push` - this command is used to upload/send files from a local repository/storage to another storage, such as a remote one like GitHub. \

- `git rm` - this command is used to remove a file from the working repository. \

- `git branch` - this command is used to check the current branch you're working on, main or master. \

- `git diff` - Git will show you the difference between the current code and the code when it was last saved. \

- `git log` - we can view the commits we have made. \

- `git checkout` - go back and see the changes in our code from a previous commit. \

- `git merge` - will take all the commits you made in this branch and insert them into the main branch, preserving your work. \

- `git status` – check the status of commits (their number, changes made).

