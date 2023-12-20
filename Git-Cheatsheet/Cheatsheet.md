# Git Cheat Sheet

## Configuration

### Set user information
```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
## Create Repository

### Initialize a new Git repository
```
git init
```

### Clone a repository from a URL
```
git clone <repository-url>
```
## Basic Commands
### Check the status of your working directory
```
git status
```

### Add changes to the staging area
```
git add <filename>
```
### Add all changes to the staging area
```
git add .
```
### Commit changes
```
git commit -m "Your commit message"
```

## Branching

### Create a new branch
```
git branch <branch-name>
```
### Switch to a branch
```
git checkout <branch-name>
```
### Create and switch to a new branch
```
git checkout -b <new-branch-name>
```
### Merge changes from one branch into another
```
git merge <branch-name>
```

## Remote Repositories

### Add a remote repository
```
git remote add <remote-name> <remote-url>
```
### Push changes to a remote repository
```
git push <remote-name> <branch-name>
```
### Pull changes from a remote repository
```
git pull <remote-name> <branch-name>
```

## Logging
### View commit history
```
git log
```
### View a simplified summary of commit history
```
git log --oneline
```
## Undoing Changes

### Discard changes in the working directory
```
git restore <filename>
```
### Unstage changes
```
git restore --staged <filename>
```
### Revert to the last commit (soft reset)
```
git reset --soft HEAD^
```
### Revert to the last commit and discard changes (hard reset)
```
git reset --hard HEAD^
```
