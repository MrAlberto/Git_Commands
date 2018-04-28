# Basic commands to use Git
- **Create a new local repository**
  - `git init`
- **Tell Git who are you**
  - `git config --global user.name "MrAlberto"`
  - `git config --global user.email "example@email.com"`
- **Checkout a repository**
  - Local repository `git clone path/to/repository`
  - Remote server `git clone username@host:/path/to/repository`
- **Add files**
  - `git add <filename>`
  - `git add -A`
- **Commit**
  - `git commit -m "Commit message"`
- **Push**
  - `git push origin master`
- **Status**
  - `git status`
- **Create a new branch**
  - `git checkout -b <branchname>`
- **Switch from one branch to another** 
  - `git checkout <branchname>`
- **List all the branches in your repo**
  - `git branch`
- **Delete a branch**
  - `git branch -d <branchname>`
- **Pull** 
  - `git pull`
- **Merge**
  - `git merge <branch>`
- **Tagging**
  - `git tags 1.0.0 <commitID>`
- **Get commit ID**
  - `git log`
---
## Useful hints
- **Use colorful git output**
  - `git config color.ui true`
- **Use interactive adding**
  - `git add -i`
- **Built-in git GUI**
  - `gitk`
- **Show log on just one line per commit**
  - `git config format.pretty oneline`

---
_Links and resorcues_
* [GitHub Help](https://help.github.com/)
