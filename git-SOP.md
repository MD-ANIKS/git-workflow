
# 🛠 Git Standard Operating Procedure (SOP)

This document outlines the standard practices for using Git and GitHub within our team to ensure clean collaboration and maintainable code.

---

## 🔖 1. Branching Strategy

- `main` – Stable production code
- `dev` – Ongoing development
- `feature/<feature-name>` – New features
- `bug/<bug-description>` – Bug fixes
- `hotfix/<issue>` – Urgent production fixes

---

## ✍️ 2. Commit Message Format

Follow this structure:

```
[type]: Short summary (max 50 characters)

Example:
feat: add user login page
fix: correct validation issue on form
```

**Types:**
- `feat` – New feature
- `fix` – Bug fix
- `chore` – Maintenance
- `docs` – Documentation
- `refactor` – Code improvements

---

## 🔁 3. Workflow Process

```text
1. Pull the latest changes from 'main'
2. Create a new branch (git switch -c feature/login)
3. Do your work and commit regularly
4. Push the branch to GitHub
5. Create a Pull Request (PR)
6. Get at least one code review
7. Merge only after approval
```

---

## 🔄 4. Merging & Rebasing

- Always `git pull --rebase` to update your branch
- Resolve conflicts locally
- Use **Squash and Merge** to keep history clean

---

## 👀 5. Code Reviews

- At least one team member must review
- Use inline comments for feedback
- Only merge when approvals are done
- Avoid large PRs – keep changes focused

---

## 🏷 6. Tagging Releases

Use [Semantic Versioning](https://semver.org/):

```bash
git tag v1.0.0
git push origin v1.0.0
```

Tags should reflect stable, tested code.

---

## ⚠️ 7. Do's and Don'ts

### ✅ Do:
- Pull latest changes before pushing
- Write clear commit messages
- Keep branches short-lived
- Review PRs promptly

### ❌ Don't:
- Commit to `main` directly
- Push broken or incomplete code
- Ignore code review feedback

---

## 📁 8. .gitignore

Use `.gitignore` to exclude:

```
node_modules/
.env
*.log
dist/
```

---

By following this Git SOP, we maintain a consistent, efficient, and collaborative development process.

