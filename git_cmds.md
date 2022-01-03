# Git Commands

## Status of a file (imaginary)

- Untracked
- Unmodified
- Modified
- Staged
- Commmited
- Remote

## Official Description

- blobs 
- trees
- tags (commits)
- refs (branches)
- ref head
- 

## Commands to move between status

```
# Untracked -> Staged
# Modified -> Staged
git add 

# Staged -> Commited
git commit

# Commited -> Remote
git push

# Remote -> Unmodified
git clone / git pull

# Staged -> Modified
git reset

# Modified -> Unmodified
git checkout

# Unmodified -> Untracked
git rm
```

## Commands to show diff info

```
# Unmodified -- Modified
git diff

# Unmodified -- Staged
git diff HEAD
```





## Misc

```
# local commands
git init
git status
git add *
git commit -m "my first commit"

# interact with server
git pull
git fetch
git -u push origin my-branch
git rebase

# version control
git log
git reflog
git checkout
git reset
git reset --hard HEAD@{2}

# branches
git branch 
git branch my-branch
git checkout master
// delete branch locally
git branch -d my-branch
// delete branch remotely
git push origin --delete my-branch
// merge to master
git checkout master
git merge my-branch
vim .gitignore

# save credentials
git config --global credential.helper store
```

