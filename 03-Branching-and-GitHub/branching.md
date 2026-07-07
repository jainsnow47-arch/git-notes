# Git Branching

## What is a Branch?

A branch is an independent line of development in Git. It allows developers to work on new features, bug fixes, or experiments without affecting the main project.

---

## Why Do We Need Branches?

When multiple developers work on the same project, making changes directly to the main branch can introduce bugs, conflicts, and unstable code.

Branches allow each developer to work independently and merge their changes only after testing.

---

## Benefits of Branching

- Develop features independently
- Fix bugs safely
- Keep the main branch stable
- Support parallel development
- Simplify collaboration

---

## Basic Workflow

```text
                 main
                   │
        ┌──────────┼──────────┐
        │          │          │
   feature-A   feature-B   bug-fix
        │          │          │
        └──────────┴──────────┘
                   │
                Merge
```

---

## Key Takeaways

- Every new feature should be developed in its own branch.
- The `main` branch should remain stable.
- Branches make collaboration easier.
- Changes are merged into the main branch after testing.

---

## My Understanding

I learned that branches allow developers to work independently without affecting the main project. This makes teamwork easier and keeps the main branch stable while new features and bug fixes are being developed.
