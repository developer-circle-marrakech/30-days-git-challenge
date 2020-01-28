# 30-days-git-challenge

Here you will found a daily challenge questions and responses (next day) as log:

### Day 01 :

**Q : To set your email address at the global (or user) level, what command would you type?**

1. git set --user email `<email>`
1. **git config --global user.email `<email>` ✔️️**
1. git config email `<email>`
1. git set --user user.email `<email>`

---

### Day 02 :

**Q : To create a Git repository, which command do you run?**

1.  git create `<project-name>`
1.  git new
1.  git new `<project-name>`
1.  **git init ✔️️ ️**

---

### Day 03 :

**Q : True or False: The git status command shows the status of the integrated repository test suite.**

1.  true
1.  **false ✔️️ ️**

---

### Day 04 :

**Q : Which command would you run to stage the changes in the `js/app.js` file?**

1.  **git add `js/app.js` ✔️️ ️**
1.  git stage `js/app.js`
1.  git commit `js/app.js`
1.  git commit `js/app.js` --to-staging-area

---

### Day 05 :

**Q : Write the basic command used to create a commit from the staged changes (don't include any flags).**

**git commit ✔️️ ️**

---

### Day 06 :

**Q : What is the name of the file used to tell Git to ignore certain files?**

1.  gitignore
1.  **.gitignore ✔️️ ️**
1.  ignore.git
1.  ignore

---

### Day 07 :

**Q : What command do you run to view the commit history of your repositor?**

1.  git history
1.  **git log ✔️️ ️**
1.  git commit -h
1.  git past

---

### Day 08 :

**Q : To create a branch, you run `git branch` . How can you create a branch and switch to it in one command?**

1.  git branch --switch `<branch-name>`
1.  git branch --checkout `<branch-name>`
1.  **git checkout -b `<branch-name>` ✔️️ ️**
1.  git checkout --create-branch `<branch-name>`

---

### Day 09 :

**Q : Write the command that would merge the awesome_feature branch with the master branch, assuming you are on the master branch.**

**git merge awesome_feature ✔️️ ️**

---

### Day 10 :

**Q : Which command will add a remote branch to the repository?**

1.  **git remote add `<name>` `<url>`✔️️ ️**
1.  git branch --remote `<name>` `<url>`
1.  git remote new `<name>` `<url>`
1.  git branch `<name>` `<url>`

---

### Day 11 :

**Q : Assuming your repo has a remote called production, what command would send all local committed changes on the master branch to that remote?**

1.  git send master production
1.  git send production master
1.  git push master production
1.  **git push production master ✔️**

---

### Day 12 :

**Q : Write the command that would remove the latest stash from the stash list and apply it to the staging area.**

**git stash pop ✔️**

---

### Day 13 :

**Q : What command would create the `c` alias for the `commit` command (at the global, or user, level)?**

1.  **git config --global alias.c commit ✔️**
1.  git config --global alias.commit c
1.  git config alias.c commit
1.  git config alias.commit c

---

### Day 14 :

**Q : Write the command that will display the diff of the README file, comparing the version in the staging area with the latest committed version.**

**git diff --staged README ✔️**

---

### Day 15 :

**Q : What is the purpose of `git filter-branch`?**

1. To perform a text search inside a particular set of branches
1. **To rewrite history by applying some operation to all commits ✔️**
1. To list all local branches except the ones filtered out by some predicate
1. To perform garbage collection on a single branch

---

### Day 16 :

**Q : Where does Git look for its subprograms (git-commit, git-diff)?**

1. PATH environment variable
1. git.binaries global config
1. **GIT_EXEC_PATH environment variable ✔️**
1. the directory where git itself is located

### Day 17 :

**Q : `git describe` looks for the nearest \_\_\_ reachable from the commit**

1. remote
1. author
1. **tag ✔️**
1. branch

---

### Day 18 :

**Q : What does a `" "` sign at the beginning of a refspec mean?**

1. That there is a one-to-many mapping between refs
1. That the remote branch may not exist
1. **That overwriting (non-fast-forward) updates are allowed ✔️ ️**
1. That authentication will be required

---

### Day 19 :

**Q :"Sparse checkout" allows you to**

1. **check out only some files from the repository into your working copy ✔️ ️**
1. check out a branch from the repository without some of its commits
1. init only the main submodule of the repository
1. clone a remote such that you get a working copy but no repository (no .git folder)

---

### Day 20 :

**Q : Git-attributes filters are used for...**

1. transforming how the repository is presented in `git status` and `git log`
1. applying text substitutions inside commits received from remotes
1. **applying text substitutions on commit/checkout ✔️ ️**
1. ignoring files based on metadata

---

### Day 21 :

**Q : A bare Git respository...**

1. has no remotes
1. has .git directory in a separate location from its working tree
1. has an empty working tree
1. **has contents of .git directory instead of a working tree ✔️ ️**

### Day 22 :

**Q : What does a commit range `branch1..branch2` mean?**

1. All commits that contain files changed between commits at branch1 and branch2
1. **All commits reachable from branch2, but not reachable from branch1 ✔️ ️**
1. All commits reachable from branch1, but not reachable from branch2
1. All commits created in the period between commits at branch1 and branch2

---

### Day 23 :

**Q : Git reflog is used to...**

1. synchronize with remote-tracking branches
1. track authors of changes
1. **store the history of updates of refs ✔️ ️**
1. store the history of merge conflicts

---

### Day 24 :

**Q :A Git tree object..**

1. **can contain references to other tree objects or blobs ✔️ ️**
1. can only contain references to blobs
1. can contain file data or references to other tree objects or blobs
1. can only contain references to other tree objects

---

### Day 25 :

**Q : When should you NOT run `git gc`?**

1. In a sparse working tree
1. When working in someone else's branch
1. When you have orphaned objects you want to restore
1. When you plan to push to a remote

## <!-- When you have orphaned objects you want to restore -->

---

### Day 26 :

**Q : If you're cloning a repository that contains submodules, they will be initialized...**

1. only after `git submodule init` and `git submodule update`
1. after `git submodule init` and `git submodule update`or if you clone with `--recursive` argument
1. only if you clone with `--recursive` argument
1. only if you clone with `--submodules` argument

 <!-- after `git submodule init` and `git submodule update`or if you clone with `--recursive` argument -->

### Day 27 :

**Q :Where is a branch stored inside a Git repository?**

1. Inside either .git/branches file or .git/packed-refs file
1. Inside .git/refs directory
1. Inside .git/packed-refs file
1. Inside either .git/refs directory or .git/packed-refs file

<!-- Inside either .git/refs directory or .git/packed-refs file -->

---

### Day 28 :

**Q : What files can be searched in using `git grep`?**

1. Current working tree and remote working tree
1. Current working tree
1. Any files on the computer
1. Any local Git trees

<!-- Any local Git trees -->

---

### Day 29 :

**Q :What can't be cryptographically signed in Git?**

1. Branches
1. Tags
1. Merge commits
1. Regular commits

## <!-- Branches -->

### Day 30 :

**Q : Which of the following is not a valid option for `credential.helper` setting?**

1. cache
1. temporary
1. store
1. no value (default)

## <!-- temporary -->
