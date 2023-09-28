# -Git-Command-Reference
This repository serves as a comprehensive reference guide for Git commands and workflows
# Git Configuration
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"

# Create a New Git Repository
git init

# Clone a Repository
git clone <repository_url>

# Basic Git Workflow
git status
git add <file>
git commit -m "Commit message"
git push
git pull

# Branching
git branch
git branch <branch_name>
git checkout <branch_name>
git merge <branch_name>
git branch -d <branch_name>

# Viewing History
git log
git log --oneline
git log --graph

# Undoing Changes
git reset <file>
git checkout <file>
git revert <commit_hash>

# Stashing Changes
git stash
git stash list
git stash apply
git stash drop

# Remote Repositories
git remote
git remote -v
git fetch <remote>
git pull <remote> <branch>
git push <remote> <branch>

# Tags
git tag
git tag <tag_name>
git push --tags
git checkout <tag_name>

# Git Ignore
# Create a .gitignore file with a list of files and directories to ignore.

# Git Aliases
# Add custom aliases in your .gitconfig file.

# Advanced Git
git rebase
git cherry-pick
git bisect
git submodule

# Git Help
git --help
git <command> --help



#Author
- MOHAsbissi01
