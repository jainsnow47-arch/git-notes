# GitHub Workflow

## Overview

GitHub allows developers to store Git repositories remotely, collaborate with teams, and synchronize local changes with the cloud.

---

## Basic Workflow

```text
Write Code
      │
      ▼
git add
      │
      ▼
git commit
      │
      ▼
Local Repository (.git)
      │
      │ git push
      ▼
GitHub (Remote Repository)
      │
      │ git pull
      ▼
Local Repository
```

---

## git push

Uploads local commits to the remote GitHub repository.

```bash
git push origin main
```

---

## git pull

Downloads the latest changes from GitHub and automatically merges them into the current branch.

```bash
git pull origin main
```

---

## git fetch

Downloads the latest changes from GitHub without merging them into the current branch.

```bash
git fetch origin
```

---

## git clone

Creates a complete local copy of a remote GitHub repository, including its commit history.

```bash
git clone <repository-url>
```

---

## Difference Between git pull and git fetch

| git pull | git fetch |
|----------|-----------|
| Downloads changes | Downloads changes |
| Automatically merges changes | Does not merge changes |
| Updates the local branch | Only updates remote tracking information |

---

## Key Takeaways

- `git push` uploads local commits.
- `git pull` downloads and merges changes.
- `git fetch` downloads changes without merging.
- `git clone` copies an entire remote repository to the local machine.

---

## My Understanding

I learned that GitHub is used to synchronize local repositories with a remote repository. `git push` uploads changes, `git pull` downloads and merges changes, `git fetch` only downloads updates without merging, and `git clone` creates a complete local copy of a remote repository.
