# Git Workflow
 
## Main Branch
 
`main` must always be stable. No experimental or unfinished work directly on `main`.
 
## Branch Naming
 
```
type/short-description
```
 
Examples: `feat/person-detection`, `fix/capture-interval`, `docs/git-workflow`
 
## Workflow
 
```bash
# 1. Update local repo
git checkout main && git pull
 
# 2. Create branch
git checkout -b type/short-description
 
# 3. Stage and commit
git add docs/development/git-workflow.md
git commit -m "docs: add git workflow"
 
# 4. Push
git push -u origin type/short-description
```
 
## Pull Request
 
Open a PR from your branch into `main`. Include what changed, why, and which issue it closes.
 
**Description example:**
 
```
## What changed
Brief description of the changes.
 
## Why
Why this change was needed.
 
Closes #9
```
 
> To close multiple issues: `Closes #9, closes #12`  
> Keywords: `closes`, `fixes`, `resolves` — issue closes automatically when PR is merged.
 
Before merging: project runs, criteria met, docs updated, reviewed if possible.
 
## After Merging
 
```bash
git checkout main && git pull
git branch -d type/short-description
```
 
## Emergency Fix
 
```bash
git checkout -b fix/short-description
git commit -m "fix: description"
```