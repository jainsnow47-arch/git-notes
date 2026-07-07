# Centralized vs Distributed Version Control

## Introduction

Version Control Systems are mainly of two types:

- Centralized Version Control System (CVCS)
- Distributed Version Control System (DVCS)

Both are used to track project history, but they work differently.

---

## Centralized Version Control System (CVCS)

In a Centralized Version Control System, all developers depend on a single central server.

The server stores the complete project history, and developers connect to it whenever they want to access or update the project.

### Advantages

- Easy to manage
- Centralized administration
- Simple workflow

### Disadvantages

- Single point of failure
- Work may stop if the server is unavailable
- Usually requires network access

### Examples

- SVN (Subversion)
- CVS

---

## Distributed Version Control System (DVCS)

In a Distributed Version Control System, every developer has a complete copy of the repository on their local machine.

Developers can work offline, create commits, and view project history without depending on the internet.

When internet becomes available, changes can be pushed to a remote repository like GitHub.

### Advantages

- Offline support
- Faster operations
- Better backup
- No single point of failure

### Disadvantages

- Slightly larger local storage
- Can be confusing for beginners initially

### Examples

- Git
- Mercurial

---

## Comparison

| Feature | CVCS | DVCS |
|----------|------|------|
| Repository | Central Server | Every Developer |
| Offline Work | ❌ No | ✅ Yes |
| Offline Commit | ❌ No | ✅ Yes |
| Single Point of Failure | ✅ Yes | ❌ No |
| Speed | Slower | Faster |
| Example | SVN | Git |

---

## Key Takeaways

- Git is a Distributed Version Control System.
- Every developer has a complete repository.
- Developers can work without internet.
- GitHub is not Git; GitHub is only a remote hosting platform.

---

## My Understanding

Today I learned the difference between Centralized and Distributed Version Control Systems. Git is a Distributed Version Control System because every developer has a complete copy of the repository, allowing them to work offline and commit changes without depending on a central server.
