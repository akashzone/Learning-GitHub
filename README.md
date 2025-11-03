# 🧠 Learning GitHub

Welcome to **Learning GitHub** — a personal repository for practicing and understanding **Git** and **GitHub**.
This repo contains notes, examples, and commands to help beginners learn version control step by step.

---

## 📘 What Is Git & GitHub?

* **Git** → A version control system that helps you track changes in your code.
* **GitHub** → A cloud platform where you can store your Git repositories and collaborate with others.

---

## ⚙️ Basic Git Setup

| Command                                            | Description                     |
| -------------------------------------------------- | ------------------------------- |
| `git --version`                                    | Check if Git is installed       |
| `git config --global user.name "Your Name"`        | Set your Git username           |
| `git config --global user.email "you@example.com"` | Set your Git email              |
| `git config --list`                                | View all configuration settings |

---

## 🏗️ Working with Repositories

| Command                            | Description                                             |
| ---------------------------------- | ------------------------------------------------------- |
| `git init`                         | Initialize a new local Git repository                   |
| `git clone <repo-url>`             | Copy (clone) a repository from GitHub                   |
| `git remote -v`                    | Show the remote repository connected to your local repo |
| `git remote add origin <repo-url>` | Link local repo to GitHub repo                          |

---

## 📁 Staging and Committing

| Command                   | Description                          |
| ------------------------- | ------------------------------------ |
| `git status`              | Show changed files                   |
| `git add <file>`          | Stage a specific file                |
| `git add .`               | Stage all files                      |
| `git commit -m "message"` | Save (commit) changes with a message |
| `git log`                 | View commit history                  |

---

## 🌿 Branching and Merging

| Command                | Description                         |
| ---------------------- | ----------------------------------- |
| `git branch`           | List all branches                   |
| `git branch <name>`    | Create a new branch                 |
| `git checkout <name>`  | Switch to a branch                  |
| `git merge <name>`     | Merge a branch into the current one |
| `git branch -d <name>` | Delete a branch                     |

---

## 🚀 Pushing and Pulling

| Command                   | Description                            |
| ------------------------- | -------------------------------------- |
| `git push origin main`    | Upload commits to GitHub (main branch) |
| `git push -u origin main` | Set the default upstream branch        |
| `git pull origin main`    | Download and merge changes from GitHub |
| `git fetch`               | Download changes without merging       |

---

## 🧹 Undoing Changes

| Command              | Description                         |
| -------------------- | ----------------------------------- |
| `git restore <file>` | Undo changes in a file (not staged) |
| `git reset <file>`   | Unstage a file                      |
| `git reset --hard`   | Undo all local changes (dangerous!) |

---

## 🔍 Helpful Shortcuts

| Command         | Description                                           |
| --------------- | ----------------------------------------------------- |
| `git diff`      | Show differences between commits or working directory |
| `git show`      | Show details about a specific commit                  |
| `git stash`     | Temporarily save changes without committing           |
| `git stash pop` | Restore stashed changes                               |

---

## 🌐 GitHub Collaboration Commands

| Command            | Description                                       |
| ------------------ | ------------------------------------------------- |
| `git fork`         | (On GitHub) Create a copy of someone’s repository |
| `git pull request` | (On GitHub) Request to merge your changes         |
| `git issue`        | (On GitHub) Report or discuss bugs and tasks      |

---

## 🏁 Summary

This repository is a hands-on space for learning how to:

* Use Git for local version control
* Connect local repos to GitHub
* Collaborate using branches, commits, and pull requests

---

### 📜 License

This project is for **learning purposes only**. Feel free to use and modify for your own Git/GitHub practice.

---

Happy Coding! 💻✨
