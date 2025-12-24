# learn-branching

Level 1: Introduction to Git Commits

Description

This level introduces the most basic Git operation — **creating commits**.
Each `git commit` creates a new snapshot of the project history.
The goal is to create two commits on the `main` branch.

![WhatsApp Image 2025-12-24 at 14 20 33_04b303fe](https://github.com/user-attachments/assets/5827f548-681c-4a90-abdd-4cba0aaa8640)


Commands Used

```bash
git commit
git commit
```


Level 2: Branching in Git

Description

This level explains how to **create and switch branches**.
Branches allow you to work on features or fixes independently from the main codebase.

![WhatsApp Image 2025-12-24 at 14 20 47_def96aea](https://github.com/user-attachments/assets/1f11b9e1-5b5f-473e-9c33-33d341b2abc7)


Commands Used

```bash
git branch bugfix
git checkout bugfix
```


Level 3: Merging in Git

Description

This level demonstrates how to **merge a feature branch into the main branch**.
Changes are first committed on the `bugfix` branch and then merged into `main`.

![WhatsApp Image 2025-12-24 at 14 21 01_a3c38c42](https://github.com/user-attachments/assets/d06ec434-972d-47bf-bde8-f5d19c0829c6)


Commands Used

```bash
git branch bugfix
git checkout bugfix
git commit
git checkout main
git commit
git merge bugfix
```



Level 4: Rebase Introduction

Description

This level introduces **rebasing**, which rewrites commit history to make it linear.
The `bugfix` branch commits are replayed on top of the `main` branch.

![WhatsApp Image 2025-12-24 at 14 21 15_c9da12ef](https://github.com/user-attachments/assets/9a18d16b-fbeb-42f3-a018-74b196bd3166)


Commands Used

```bash
git branch bugfix
git checkout main
git checkout bugfix
git commit
git checkout main
git commit
git checkout bugfix
git rebase main
```
