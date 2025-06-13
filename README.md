

## 🧰 Basic Git Guide

This guide covers the essential Git commands to get started with this repository.
Refer: https://basic-git-guide.vercel.app and [git_cheat_sheet.pdf](https://github.com/pyastrolab/basic-git-guide/git_cheat_sheet.pdf)

### 📦 Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 🔧 Set Up Git (if you haven't already)

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

---

### 🌿 Create a New Branch

```bash
git checkout -b your-feature-branch
```

> Use a descriptive name like `fix/readme-typo` or `feature/user-login`.

---

### 📝 Make Changes and Commit

```bash
git add .
git commit -m "Your meaningful commit message"
```

---

### 🔄 Pull Latest Changes

Make sure your branch is up to date before pushing:

```bash
git pull origin main  # or 'master' if your repo uses that
```

---

### 🚀 Push Your Changes

```bash
git push origin your-feature-branch
```

---

### 📥 Create a Pull Request

1. Go to the GitHub repository in your browser.
2. Click **"Compare & pull request"**.
3. Add a title and description for your PR.
4. Submit the pull request.

---

### 🧹 Optional: Delete Branch After Merge

```bash
git branch -d your-feature-branch        # delete local
git push origin --delete your-feature-branch  # delete remote
```

