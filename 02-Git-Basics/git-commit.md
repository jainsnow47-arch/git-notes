# git commit

## Overview

The `git commit` command is used to permanently save the staged changes in the local Git repository. Each commit creates a snapshot of the project, allowing developers to track the project's history.

---

## Syntax

```bash
git commit -m "Commit message"
```

---

## What Does `git commit` Do?

- Saves staged changes permanently in the local repository.
- Creates a snapshot of the project.
- Records the commit message along with the author's name and email.
- Does **not** upload changes to GitHub.

---

## Why Are Commit Messages Important?

A commit message briefly describes the changes made in the project.

Example:

```bash
git commit -m "Add login page"
```

Good commit messages make the project history easier to understand.

---

## Key Points

- Only staged files are committed.
- Commits are stored in the local repository (`.git`).
- GitHub is not updated until `git push` is executed.
- Every commit represents a snapshot of the project.

---

## Git Commit Workflow

```text
Working Directory
        │
        │ git add
        ▼
Staging Area
        │
        │ git commit
        ▼
Local Repository (.git)
        │
        │ git push
        ▼
GitHub
```

---

## My Understanding

I learned that `git commit` permanently saves the staged changes in the local Git repository. It creates a snapshot of the project and records the project history. However, these commits remain local until they are pushed to GitHub using `git push`.
