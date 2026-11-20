# Cloud and DevOps - Practical 4

**Implementation of Version Control Operations using Git & GitHub**

Name: Saloni Singh
Course: B.Tech, Semester V
Subject: Cloud and DevOps

## Aim
To understand and implement basic version control operations using Git and GitHub.

## Repository Structure

| File | Description |
|------|-------------|
| `README.md` | Project documentation |
| `login.py` | Sample file created on a feature branch and merged into main |

## Git Operations Performed

| Operation | Command |
|-----------|---------|
| Configure user | `git config --global user.name` / `user.email` |
| Initialize repository | `git init -b main` |
| Check status | `git status` |
| Stage files | `git add <file>` |
| Commit changes | `git commit -m "message"` |
| View history | `git log --oneline` |
| View changes | `git diff` |
| Create branch | `git branch feature-login` |
| Switch branch | `git switch feature-login` |
| Merge branch | `git merge feature-login` |
| Delete branch | `git branch -d feature-login` |
| Add remote | `git remote add origin <url>` |
| Push to GitHub | `git push -u origin main` |

## Workflow

1. Created a local repository and made the first commit.
2. Modified files and tracked changes using `git diff`.
3. Created a feature branch, committed work, and merged it into `main`.
4. Pushed the repository to GitHub.

## Conclusion
Git tracks changes, supports branching and merging, and GitHub hosts the repository online for backup and collaboration.
