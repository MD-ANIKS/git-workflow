
# 📘 Git & GitHub Basics

## 🔍 Why We Use Git & GitHub
- **Track changes** in code over time
- **Collaborate** with team members easily
- **Back up** and sync code using GitHub
- Keep code **organized** and **versioned**

---

## 🚀 How It Works (In Short)

1. `git init` – Start tracking a project.
2. `git add` – Stage your changes.
3. `git commit` – Save a snapshot with a message.
4. `git push` – Upload changes to GitHub.
5. `git pull` – Get latest changes from GitHub.
6. `git branch` – Create or switch branches.
7. `git merge` – Combine changes from branches.
8. Pull Request – Ask to merge your code on GitHub.
9. Merge – Combine after review.

---

## 🤝 Team Workflow

```
1. Clone the repo
2. Create a new branch
3. Do your changes and commit
4. Push your branch
5. Create a pull request
6. Review and merge
```

---

## 🧠 Tips

- Pull before you push
- Commit often, with clear messages
- Use `.gitignore` to skip unwanted files
- Don’t work directly on `main` branch

---

## 🛠 Useful Commands

```bash
git clone <url>        # Download project
git checkout -b name   # Create & switch to new branch
git status             # See changes
git log                # View commit history
```

---

## ✅ Summary

Git helps manage code. GitHub helps share and work together. Use both to keep your team fast, safe, and in sync.

---

## 🧪 More Useful Git Commands

### 🔁 `git rebase`
- Reapply commits on top of another base tip.
- Keeps history clean.
```bash
git checkout feature
git rebase main
```

### 🔄 `git switch`
- Easier way to switch branches (modern alternative to `checkout`).
```bash
git switch dev
```

### 🌱 `git switch -c <branch-name>`
- Create and switch to a new branch.
```bash
git switch -c feature-xyz
```

### 🏷 `git tag`
- Mark specific points in history as important (e.g., v1.0).
```bash
git tag v1.0
git push origin v1.0
```
