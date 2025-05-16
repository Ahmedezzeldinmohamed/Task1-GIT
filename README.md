# Git Training Project – Fawry DevOps Internship

This is a simple project to practice basic Git commands like:
- Creating branches
- Making commits
- Using reset and reflog
- Performing rebase

---

## 📌 What I did:

### 🟢 Part 1: On the `develop` branch
- Created two files: `file1` and `file2`
- Made two separate commits
- Used `git reset --hard` to go back to the first commit
- Used `git reflog` to find and recover the lost commit

### 🟡 Part 2: On the `alpha` branch
- Created a file `file3` and committed it
- Switched back to `develop` and created `file4` with a commit
- Viewed the commit history using `git log --oneline --graph`

### 🔁 Part 3: Rebase
- Rebasing `develop` onto `alpha`
- Then rebased `alpha` onto `develop`
- Checked the commit history after rebasing

---

## 🛠 Tools used:
- Git CLI
- Ubuntu Terminal

---

## ✅ Purpose:
- Understand how to use reset and reflog
- Practice working with multiple branches
- Learn how to rebase and organize commits


