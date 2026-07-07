# git status

## Overview

The `git status` command displays the current state of a Git repository. It shows which files are untracked, modified, staged, or ready to be committed.

---

## Syntax

```bash
git status
```

---

## File States in Git

### 1. Untracked

A newly created file that Git is not tracking.

Example:

```text
Untracked files:
    app.js
```

To start tracking the file:

```bash
git add app.js
```

---

### 2. Staged

After using `git add`, the file moves to the Staging Area and is ready to be committed.

Example:

```text
Changes to be committed:
    new file: app.js
```

---

### 3. Tracked

Once the staged file is committed using `git commit`, Git starts tracking it.

Tracked files become part of the project's history.

---

### 4. Modified

If a tracked file is edited after a commit, Git marks it as **Modified**.

Example:

```text
Changes not staged for commit:
    modified: app.js
```

To stage the modified file again:

```bash
git add app.js
```

---

## Git File Lifecycle

```text
Create File
      │
      ▼
Untracked
      │
      │ git add
      ▼
Staged
      │
      │ git commit
      ▼
Tracked
      │
(Edit File)
      ▼
Modified
      │
      │ git add
      ▼
Staged
```

---

## Why Use `git status`?

- View the current state of the repository
- Identify untracked files
- Check staged changes
- Detect modified files
- Verify whether the working tree is clean

---

## Key Takeaways

- `git status` does not modify the repository.
- It only displays the current status of files.
- It is one of the most frequently used Git commands.

---

## My Understanding

I learned that every file in Git moves through different states: **Untracked → Staged → Tracked → Modified**. The `git status` command helps me identify the current state of each file so I know what action to take next.
