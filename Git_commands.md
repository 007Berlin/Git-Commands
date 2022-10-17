# Git Commands
### What is Git -
Git is a version control system used for tracking changes in computer files. It is generally used for source code management in software development.

    Git is used to tracking changes in the source code.
    The distributed version control tool is used for source code management.
    It allows multiple developers to work together.
    It supports non-linear development through its thousands of parallel branches.

### 1. init - It creates an empty Git repository.

### 2. config - To introduce git with username and email id.

a) For username -

b) For email id -

### 3. status - It displays the state of the working directory.


### 4. add -

a) git add filename - To add files to the staging area to track the files.

b) git add . - To add all the files available in the repository.

### 5. commit - To capture a snapshot of the project's currently staged changes (Its like clt+s)

### 6. branch -

a) check branches - To list all the branches and to check the present branch in the Github repo.

Note : If initially your branch is master then change branch name from master to main, so that it can be compactable with github.

b) new branch - To create a new branch.

c) switch branch - To switch from the new branch and move to the main branch.

d) delete branch - To delete a branch from the git repo.

### 7. remote -

a) git remote add origin - To link the git repository in which user wants to push their local code. It helps in creating connections with other repositories.

b) git remote -v - To list the remote connection user has to other repositories.

### 8. push - To push the branch or to push the changes in the branch to the GitHub repo.

### 9. log - To display all the commits in a repository's history.

### 10. merge - To merge the current branch into the specified branch (main).

NOTE - we are on the developer1 branch so to merge we have to checkout in the main branch than only we are able to merge onto main.

### 11. restore - To unstage or even discard uncommitted local changes.

### 12. reset - To undo the recent changes that are to be committed.

### 13. stash - To take your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy

### 14. clone - To point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.

### 15. pull - To pull the new changes from git repository to local machine.