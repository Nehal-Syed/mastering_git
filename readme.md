# Git & GitHub Advanced Concepts

This repository contains my hands-on practice and learning exercises for advanced Git and GitHub workflows. The goal of this project is to understand how professional teams collaborate using Git, manage code changes, resolve conflicts, and maintain clean version history.

---

## 📚 Topics Covered

During this project, I learned and practiced:

### 🌿 Branching

* Creating and managing branches
* Working on features in isolated branches
* Switching between branches

### 🔀 Merging

* Merging feature branches into the main branch
* Understanding fast-forward and non-fast-forward merges
* Resolving merge conflicts

### 🛠️ Git Reset

* `git reset --soft`
* `git reset --mixed`
* `git reset --hard`
* Understanding how reset affects commits, staging, and working directory

### 📦 Git Stash

* Saving uncommitted changes temporarily
* Applying stashed changes
* Managing multiple stashes

### ↩️ Git Revert

* Reverting commits safely
* Preserving commit history
* Understanding the difference between reset and revert

### 📜 Git Logs

* Viewing commit history
* Using log formatting options
* Tracking branch and merge history

---

## 🎯 Learning Objectives

By completing this project, I gained practical experience with:

* Git branching strategies
* Collaborative development workflows
* Merge conflict resolution
* Version control best practices
* History management and recovery
* Safe rollback techniques
* Repository maintenance

---

## 🚀 Commands Practiced

### Branching

```bash
git branch
git checkout -b feature-branch
git switch feature-branch
```

### Merging

```bash
git checkout main
git merge feature-branch
```

### Reset

```bash
git reset --soft HEAD~1
git reset --mixed HEAD~1
git reset --hard HEAD~1
```

### Stash

```bash
git stash
git stash list
git stash apply
git stash pop
```

### Revert

```bash
git revert <commit-hash>
```

### Logs

```bash
git log
git log --oneline
git log --graph --all
```

---

## 🏆 Key Takeaways

* Git branches allow independent development without affecting the main codebase.
* Merge conflicts are normal and can be resolved safely.
* Reset and Revert serve different purposes and should be used carefully.
* Stash is useful for temporarily saving work in progress.
* Git logs provide valuable insights into project history.
* Proper Git workflows improve collaboration and code quality.

---

## 📄 License

This repository is for learning and educational purposes.
