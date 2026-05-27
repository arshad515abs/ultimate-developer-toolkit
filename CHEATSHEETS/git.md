# Git Cheatsheet

## Setup
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

## Daily Commands
- Clone: `git clone <url>`
- Status: `git status`
- Add: `git add .`
- Commit: `git commit -m "feat: ..."`
- Push: `git push origin main`
- Pull: `git pull`

## Branching
- New branch: `git checkout -b feature-branch`
- Switch: `git checkout main`
- Merge: `git merge feature-branch`

## Pro Tips
- `git stash`
- `git rebase -i HEAD~3`
- `git reflog`