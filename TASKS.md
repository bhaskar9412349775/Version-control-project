
---

## ** Create `TASKS.md`**
This file list **everything I did in order**.

```markdown
# TASKS.md — Execution Log

### Step 1 — Setup
- Created local folder and ran `git init`
- Added README.md, .gitignore, docs folder
- Commit: `Initial project setup`

### Step 2 — Push main
- Renamed branch to main
- Linked to GitHub repo
- Pushed main branch

### Step 3 — Create dev branch
- `git checkout -b dev`
- `git push -u origin dev`

### Step 4 — Create feature branch
- `git checkout -b feature/add-readme`
- Added "Task Progress" section to README.md
- Commit: `feat: add README tasks section`
- Pushed feature branch

### Step 5 — PR feature → dev
- Opened PR #1
- Merged into dev (no conflicts)

### Step 6 — PR dev → main
- Opened PR #2
- Merged into main (no conflicts)

### Step 7 — Tag release
- Created tag v1.0.0 and pushed it
