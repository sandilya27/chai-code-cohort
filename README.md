# Welcome to Git and GitHub at ChaiCode Cohort🚀

## Introduction

Welcome aboard! This guide will walk you through everything you need to know about using Git and GitHub at **ChaiCode Cohort**. As a collaborative development platform, Git helps us maintain code quality, track changes, and work together efficiently.

## Basics of Git and GitHub

### What is Git?

Git is a distributed [version control](https://en.wikipedia.org/wiki/Version_control) system that helps us track changes in our codebase. Think of it as a time machine for your code that allows you to:

- Track all changes made to your code
- Collaborate with team members without conflicts
- Maintain different versions of your project
- Recover from mistakes easily

### What is GitHub?

GitHub is a **cloud-based** platform that provides a centralized location to store, manage, and collaborate on Git repositories.

---

## Installation & Setup

### Installing Git

#### windows

1. Download Git from git-scm.com
2. Run the installer, using default settings
3. Verify installation by opening Command Prompt:

```bash
git --version
```

#### macOS

```bash
brew install git
```

#### Linux (Ubuntu/Debian)

```bash
sudo apt-get update
sudo apt-get install git
```

### Initial Configuration

Set up your identity:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@gmail.com"
```

### GitHub Account Setup

1. Visit GitHub.com
2. Click "Sign Up"
3. Use your email address
4. Complete the verification process

---

### Cloning the ChaiCode Repository

Clone the repository:

```bash
git clone https://github.com/sandilya27/chai-code-cohort.git
```

Navigate into the cloned folder:

```bash
cd example-repo
```

---

## Essential Git Commands

### Daily Workflow Commands

- Check repository status:

```bash
git status
```

- Create a new branch:
  
```bash
git checkout -b feature/docs
```

- Stage changes:

```bash
git add .            # Add all changes
git add index.js     # Add specific file
```

- Commit changes:
  
```bash
git commit -m "feat: Add login with google"
```

- Push changes:
  
```bash
git push origin feature/docs
```

- Get latest updates:
  
```bash
git pull origin main
```

### Some Other Usefull Commands

| Commands        | Description                                 |
|:---------------:|:-------------------------------------------:|
| `git status`    | View the status of your repo                |
| `git log`       | View commit history                         |
| `git stash`     | Temporarily save uncommitted changes        |
| `git stash pop` | Apply stashed changes and remove from stash |

---
