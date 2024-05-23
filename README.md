
# Git Commands Cheatsheet

Welcome to the Git Commands Cheatsheet repository! This repository contains a comprehensive list of common Git commands, grouped by their functionalities. It serves as a handy reference guide for both beginners and experienced developers to quickly look up Git commands and their usage.

## Table of Contents
- [Introduction](#introduction)
- [Configuration](#configuration)
- [Creating Repositories](#creating-repositories)
- [Basic Snapshotting](#basic-snapshotting)
- [Branching & Merging](#branching--merging)
- [Inspection & Comparison](#inspection--comparison)
- [Undoing Changes](#undoing-changes)
- [Remote Repositories](#remote-repositories)
- [Collaboration](#collaboration)
- [Working with Tags](#working-with-tags)
- [Miscellaneous](#miscellaneous)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This cheatsheet provides a thorough reference guide of essential Git commands, making it easy to understand and use Git for version control.

## Configuration

### Setting up your Git environment
- Set your name for Git commits:
  ```sh
  git config --global user.name "Your Name"
  ```
- Set your email for Git commits:
  ```sh
  git config --global user.email "your_email@example.com"
  ```
- List all Git configurations:
  ```sh
  git config --list
  ```

## Creating Repositories

### Initialize a new Git repository
- Create a new repository:
  ```sh
  git init
  ```

## Basic Snapshotting

### Staging and committing changes
- Add file contents to the index:
  ```sh
  git add <file>
  ```
- Commit changes:
  ```sh
  git commit -m "Your commit message"
  ```

## Branching & Merging

### Managing branches and merging changes
- List all branches:
  ```sh
  git branch
  ```
- Create a new branch:
  ```sh
  git branch <branch-name>
  ```
- Switch to a branch:
  ```sh
  git checkout <branch-name>
  ```
- Merge branches:
  ```sh
  git merge <branch-name>
  ```

## Inspection & Comparison

### Checking status and comparing changes
- Show the working tree status:
  ```sh
  git status
  ```
- Show commit logs:
  ```sh
  git log
  ```

## Undoing Changes

### Reverting changes and resetting states
- Restore working tree files:
  ```sh
  git restore <file>
  ```
- Unstage file changes:
  ```sh
  git reset <file>
  ```

## Remote Repositories

### Managing remote repositories
- Add a remote repository:
  ```sh
  git remote add <name> <url>
  ```
- List all remote repositories:
  ```sh
  git remote -v
  ```

## Collaboration

### Working with remote branches and synchronization
- Fetch from and integrate with another repository or a local branch:
  ```sh
  git pull
  ```
- Update remote refs along with associated objects:
  ```sh
  git push
  ```

## Working with Tags

### Creating and managing tags
- Create a new tag:
  ```sh
  git tag <tag-name>
  ```

## Miscellaneous

### Other useful Git commands
- Display help information about Git:
  ```sh
  git help
  ```

## Contributing

Contributions are welcome! If you have more commands, improvements, or examples, feel free to open a pull request.

## License

This project is licensed under the MIT License.

## How This Cheatsheet Was Created

I created this Git Commands Cheatsheet to provide a helpful reference for developers. Here’s how I created and pushed this cheatsheet to GitHub:

1. **Initialize the Local Repository**:
   ```sh
   git init
   ```
2. **Add and Commit the Cheatsheet**:
   ```sh
   git add README.md
   git commit -m "Initial commit with Git commands cheatsheet"
   ```
3. **Create a Remote Repository on GitHub**:
   - Go to GitHub, create a new repository named `git-commands-cheatsheet`.
4. **Add the Remote Repository**:
   ```sh
   git remote add origin https://github.com/<your-username>/git-commands-cheatsheet.git
   ```
5. **Push to GitHub**:
   ```sh
   git push -u origin main
   ```

Thank you for using this cheatsheet! Happy coding!
```

Replace `<your-username>` with your actual GitHub username. This README provides clear instructions and context for the repository, making it easy for others to understand and use your Git commands cheatsheet.
