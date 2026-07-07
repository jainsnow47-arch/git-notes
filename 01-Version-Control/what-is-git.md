# What is Git?

## Definition

Git is a Distributed Version Control System (DVCS) software that helps developers track and manage changes made to a project over time.

It records the history of a project, allowing developers to restore previous versions, collaborate with others, and maintain different versions of the same project efficiently.

---

## Why do we need Git?

Git helps developers keep track of every change made to a project. Instead of creating multiple copies such as `project_final` or `project_latest`, Git stores the complete history of changes in an organized way.

It also makes collaboration easier by allowing multiple developers to work on the same project without sharing ZIP files.

---

## How does Git Work?

Git follows a simple workflow.

```
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
Remote Repository (GitHub)
```

- `git add` moves changes to the Staging Area.
- `git commit` saves a snapshot in the Local Repository.
- `git push` uploads local commits to GitHub.

---

## What is a Git Repository?

A Git Repository is a project directory that contains a hidden `.git` folder.

This folder allows Git to track changes and maintain the complete history of the project.

Without the `.git` folder, the project is just a normal folder and is not managed by Git.

---

## What is the .git Folder?

The `.git` folder is created when we run:

```bash
git init
```

It is a hidden folder that stores:

- Commit history
- Branch information
- Repository configuration
- References
- Git metadata

The project files remain outside the `.git` folder, while Git stores only the information required to manage the project's history.

---

## Key Features

- Tracks project history
- Allows rollback to previous versions
- Supports team collaboration
- Works offline
- Maintains a complete commit history
- Fast and lightweight

---

## Key Takeaways

- Git is a software, not a website.
- Git is a Distributed Version Control System.
- Git works locally on the developer's machine.
- The `.git` folder stores the repository history and metadata.
- GitHub is a remote hosting platform used to store Git repositories online.

---

## My Understanding

Today I learned that Git is not GitHub. Git is a software installed on my local machine that tracks project history. The `.git` folder is the core of a Git repository because it stores all the information required to manage commits, branches, and project history.
