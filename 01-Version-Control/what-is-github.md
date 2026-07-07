# What is GitHub?

## Definition

GitHub is a cloud-based platform that hosts Git repositories online. It allows developers to store, manage, and share their projects, making collaboration easier for individuals and teams.

---

## Why do we need GitHub?

Git stores all commits and project history only in the local repository on our computer.

If the laptop is lost, damaged, or the hard drive fails before pushing the changes, the local repository may also be lost.

GitHub solves this problem by storing a copy of the repository in the cloud. Once the project is pushed to GitHub, it can be accessed from any computer with internet access.

GitHub also provides a central place where team members can collaborate on the same project.

---

## How GitHub Works

The basic workflow is:

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
GitHub (Remote Repository)
```

Git manages the project locally, while GitHub stores a remote copy of the repository online.

---

## Features of GitHub

- Cloud-based repository hosting
- Team collaboration
- Remote backup of projects
- Access projects from anywhere
- Track project history
- Share repositories with others
- Open Source collaboration

---

## Advantages

- Protects projects from local system failures
- Makes collaboration simple
- Stores a remote backup of the repository
- Easy to share projects using a repository link
- Provides access from multiple devices

---

## Key Takeaways

- GitHub is **not Git**.
- GitHub is a cloud platform for hosting Git repositories.
- GitHub stores the remote repository.
- Git works locally, while GitHub works online.
- Developers use Git to manage code and GitHub to share and collaborate on projects.

---

## Common Interview Mistakes

❌ Git and GitHub are the same thing.

✔ Git is a Distributed Version Control System.

✔ GitHub is a cloud platform that hosts Git repositories.

---

❌ GitHub stores the only copy of the project.

✔ Git stores the local repository, while GitHub stores a remote copy after using `git push`.

---

## My Understanding

I learned that GitHub was created because Git only manages the project locally. GitHub stores a remote copy of the repository in the cloud, allowing developers to recover their work, collaborate with team members, and access projects from different devices.
