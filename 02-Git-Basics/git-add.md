# git add

## Overview

The `git add` command is used to move changes from the Working Directory to the Staging Area. It prepares files for the next commit but does not create a commit.

---

## Syntax

```bash
git add <file-name>
git add .
```

---

## What Does `git add` Do?

- Moves files to the Staging Area
- Prepares changes for the next commit
- Does not save changes permanently
- Allows developers to choose which files to commit

---

## Common Commands

### Stage a specific file

```bash
git add app.js
```

Only `app.js` is moved to the Staging Area.

---

### Stage all files

```bash
git add .
```

All modified and new files in the current directory are moved to the Staging Area.

---

## Why is the Staging Area Important?

The Staging Area allows developers to decide exactly which changes should be included in the next commit.

For example, if 10 files are modified but only 2 are ready, only those 2 files can be staged and committed.

---

## Key Points

- `git add` does not create a commit.
- It prepares files for the next commit.
- Files remain in the Staging Area until committed.

---

## My Understanding

I learned that `git add` is used to prepare files for a commit by moving them to the Staging Area. It does not permanently save changes; that happens only after running `git commit`.
