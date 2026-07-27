# Git Notes
Git is a version control system used to track changes in files and collaborate with others.

## 1. Install Git
- Download Git from the official website.
- Verify installation:
  - `git --version`
  - or `git version`

## 2. Configure Git
- Set your name:
  - `git config --global user.name "Your Name"`
- Set your email:
  - `git config --global user.email "your_email@example.com"`
- View configuration:
  - `git config --list`

## 3. Start a new repository
- Create a new repository:
  - `git init`
- Check status:
  - `git status`

## 4. Track files
- Add a specific file:
  - `git add file_name`
- Add all files:
  - `git add .`
- Commit changes:
  - `git commit -m "Your message"`

## 5. See history
- View commit history:
  - `git log`
- Short log view:
  - `git log --oneline`
- See a specific commit:
  - `git show <commit_id>`

## 6. Undo and revert
- Unstage files:
  - `git reset`
- Reset to a previous commit:
  - `git reset --hard <commit_id>`
- Revert a commit:
  - `git revert <commit_id>`

## 7. Branches
- Create a new branch:
  - `git checkout -b branch_name`
- Switch branch:
  - `git checkout branch_name`
- List branches:
  - `git branch`
- Merge branch:
  - `git merge branch_name`
- Delete branch:
  - `git branch -D branch_name`

## 8. Remote and GitHub
- Add a remote repository:
  - `git remote add origin <repo_url>`
- Push changes:
  - `git push -u origin main`
- Pull changes:
  - `git pull origin main`

## 9. Useful everyday commands
- `git status`
- `git add .`
- `git commit -m "message"`
- `git log --oneline`
- `git checkout -b feature`
- `git push`

## 10. Common beginner notes
- Always check `git status` before committing.
- Use clear commit messages.
- Commit small changes often.
- Pull before pushing when working with others.

## Example workflow
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <repo_url>
git push -u origin main
```
