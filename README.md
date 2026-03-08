# Git Basics – Class Instructions

## Overview

This repository is created for learning **Git fundamentals**.
Students will practice basic Git commands, understand version control, and learn how developers collaborate using Git and GitHub.

---

## Prerequisites

Before starting this class, make sure you have:

* Git installed on your system
* A GitHub account
* Basic understanding of command line (Terminal / CMD)

To check Git installation:

```
git --version
```

---

## Step 1: Clone the Repository

Clone this repository to your local machine.

```
git clone https://github.com/your-username/git-class-practice.git
```

Move into the project directory:

```
cd git-class-practice
```

---

## Step 2: Check Repository Status

Use the following command to check the current status of files:

```
git status
```

Short format:

```
git status -s
```

---

## Step 3: Create a New File

Create a new file for practice.

Example:

```
student-name.txt
```

Add your name and save the file.

---

## Step 4: Add File to Staging Area

Add the file to Git staging area.

```
git add student-name.txt
```

To add all files:

```
git add .
```

---

## Step 5: Commit the Changes

Commit the changes with a meaningful message.

```
git commit -m "Added student practice file"
```

---

## Step 6: Push Changes to GitHub

Push the committed changes to the remote repository.

```
git push origin main
```

---

## Git Workflow

Typical Git workflow used in DevOps projects:

```
Working Directory
        ↓
git add
        ↓
Staging Area
        ↓
git commit
        ↓
Local Repository
        ↓
git push
        ↓
Remote Repository (GitHub)
```

---

## Common Git Commands

| Command    | Purpose                     |
| ---------- | --------------------------- |
| git init   | Initialize repository       |
| git clone  | Copy repository from GitHub |
| git status | Check file status           |
| git add    | Add files to staging area   |
| git commit | Save changes                |
| git push   | Upload changes to GitHub    |
| git pull   | Download latest changes     |
| git branch | Create branch               |
| git merge  | Merge branches              |

---

## Best Practices

* Always write meaningful commit messages
* Pull latest code before starting work
* Work in branches when developing new features
* Avoid committing unnecessary files

---

## Objective of this Class

After completing this exercise, students should understand:

* What is Git
* Basic Git commands
* Git workflow
* How developers collaborate using GitHub

---

Happy Learning 🚀
