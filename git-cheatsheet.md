# Git Command Cheat Sheet

## 1. Check Git Version

`git --version`

git version 2.47.0.windows.2
---

## 2. Configure Username

`git config --global user.name "Your Name"`

git config --global user.name"aphonemyat63"
---

## 3. Configure Email

`git config --global user.email "your@email.com"`

git config --global user.email"aphonemyat63@gmail.com"
---

## 4. Display Configuration

`git config --list`

git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
core.editor="C:\Users\Students\AppData\Local\Programs\Microsoft VS Code\bin\code" --wait

---

## 5. Clone Repository

`git clone repository-url`

Cloning into 'dti412-lab01'...
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (5/5), done.
---

## 6. Check Status

`git status`

git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
---

## 7. Add Files

`git add .`

Purpose: Add all modified files to staging.

---

## 8. Commit Changes

`git commit -m "message"`

Purpose: Save changes locally.

---

## 9. Upload to GitHub

`git push`

Purpose: Upload local commits to GitHub.

---

## 10. Download Updates

`git pull`

Purpose: Download changes from GitHub.

---

## 11. View Commit History

`git log --oneline`

Purpose: Display project history.

---

## 12. Create Branch

`git branch branch-name`

Purpose: Create a new branch.

---

## 13. Switch Branch

`git checkout branch-name`

Purpose: Change to another branch.

---

## 14. Merge Branch

`git merge branch-name`

Purpose: Merge another branch into the current branch.
