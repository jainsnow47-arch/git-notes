# Git Configuration

## Overview

Before making the first commit, Git needs to know who is creating the commits. This is done by configuring the user's name and email address.

---

## Why Do We Configure Git?

Git records the author's information with every commit. This makes it possible to identify who created or modified the project history.

---

## Configure User Name

```bash
git config --global user.name "Your Name"
```

---

## Configure Email Address

```bash
git config --global user.email "your@email.com"
```

---

## What Does `--global` Mean?

The `--global` option applies the configuration to all Git repositories on the current computer for the current user.

This means you only need to configure your name and email once.

---

## Key Points

- Git stores the author's name and email with every commit.
- Configuration is usually done only once.
- `--global` applies the settings to all repositories.

---

## My Understanding

I learned that Git configuration is required before creating commits because Git needs to know the author's identity. Using the `--global` option allows me to configure my name and email once, and Git automatically uses these details for every repository on my computer.
