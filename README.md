
# 🔄 Revert Example

A simple project to demonstrate how to revert commits in a Git repository. Learn to undo or roll back specific commits using the `git revert` command while preserving the commit history.

---

## 📖 Overview

This project provides a step-by-step guide to using the `git revert` command. Unlike `git reset`, `git revert` creates a new commit that undoes changes made by a previous commit, ensuring the repository's history remains intact.

---

## 🛠️ Getting Started

Follow these steps to get started with the project:

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/Kirankumarvel/revert-example.git
```

### 2. Navigate to the Project Directory

Move into the project folder:

```bash
cd revert-example
```

### 3. Make Changes to Files

Modify files in the repository, such as editing `test.txt` or adding new content.

### 4. Stage and Commit Changes

After making changes, stage and commit them:

```bash
git add .
git commit -m "Updated test.txt with new changes"
```

### 5. Revert a Commit

To revert a specific commit:

1. Find the commit hash with:

   ```bash
   git log
   ```

2. Use the `git revert` command with the commit hash:

   ```bash
   git revert <commit-hash>
   ```

### 6. Push Changes to GitHub

Push the changes, including the revert commit, back to the remote repository:

```bash
git push origin main
```

---

## 📋 Commands Overview

- **`git revert <commit-hash>`:** Reverts the specified commit by creating a new commit that undoes its changes.
- **`git log`**: Displays the commit history, including commit hashes.
- **`git add .`**: Stages all changes in the current directory for commit.
- **`git commit -m "<message>"`**: Commits staged changes with a descriptive message.
- **`git push origin main`**: Pushes the local changes to the `main` branch on GitHub.

---

## 🙌 Contributing

Contributions are welcome! Feel free to fork this repository, make your changes, and submit a pull request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

