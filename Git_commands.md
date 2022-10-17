# Git Commands
### What is Git -
Git is a version control system used for tracking changes in computer files. It is generally used for source code management in software development.
    
   * Git is used to tracking changes in the source code.
   * The distributed version control tool is used for source code management.
   * It allows multiple developers to work together.
   * It supports non-linear development through its thousands of parallel branches.

### 1. init - It creates an empty Git repository.
```
Example:- git init
```
![1  git init](https://user-images.githubusercontent.com/89749940/196072663-6d31c65f-33d7-477b-b33a-9bbf8d85576e.png)

### 2. config - To introduce git with username and email id.

a) For username -
```
Example:- git config --global user.name "your_username"
```
![2(a)  config username](https://user-images.githubusercontent.com/89749940/196073688-a724a9cf-aa8d-413b-a875-09ca573c93d9.png)

b) For email id -
```
Example:- git config --global user.email "your_email@gmail.com"
```
![2(b)  config email](https://user-images.githubusercontent.com/89749940/196073729-3661f353-357c-4608-b314-2339899c9258.png)

### 3. status - It displays the state of the working directory.
```
Example:- git status
```
![3  git status](https://user-images.githubusercontent.com/89749940/196073755-d4fd67ed-0bf5-4967-9bc7-a28af2cb8550.png)

### 4. add -

a) git add filename - To add files to the staging area to track the files.
```
Example:- git add "filename"
```
![4(a)  git add Git_commands md](https://user-images.githubusercontent.com/89749940/196073786-c3d11e6f-983e-4b69-a241-430fbdf12a8d.png)

b) git add . - To add all the files available in the repository.
```
Example:- git add .
```
![4(b)  git add ](https://user-images.githubusercontent.com/89749940/196073804-2f5d0c2a-3ffb-4263-ac9a-02d7b20f6f78.png)

### 5. commit - To capture a snapshot of the project's currently staged changes (Its like clt+s).
```
Example:- git commit -m "Message"
```
![5  git commit](https://user-images.githubusercontent.com/89749940/196073827-2be9a385-f217-446e-b50e-620b6f2c0396.png)

### 6. branch -

a) check branches - To list all the branches and to check the present branch in the Github repo.
```
Example:- git branch
```
![6(a)  git branch](https://user-images.githubusercontent.com/89749940/196073856-279a88e6-c542-4b59-a699-73586201c4b5.png)

Note : If initially your branch is master then change branch name from master to main, so that it can be compactable with github.
```
Example:- git branch -M main
```
![6(a)(Note)  git branch -M main](https://user-images.githubusercontent.com/89749940/196073875-a42e39ad-ed32-4497-97b2-d57addb41447.png)

b) new branch - To create a new branch.
```
Example:- git branch developer1
```
![6(b)  git branch developer1](https://user-images.githubusercontent.com/89749940/196073917-da768de6-61b0-4acd-9429-21d7da07e416.png)

c) switch branch - To switch from the new branch and move to the main branch.
```
Example:- git checkout main
```
![6(c)  git checkout developer1](https://user-images.githubusercontent.com/89749940/196073959-54f44780-6769-4a8a-9aec-fe308348c27f.png)

d) delete branch - To delete a branch from the git repo.
```
Example:- git branch -d developer1
```
![6(d)  git branch -d developer1](https://user-images.githubusercontent.com/89749940/196074016-b0bcf21b-fe9b-46b6-b77d-0da45e8be0c2.png)

### 7. remote -

a) git remote add origin - To link the git repository in which user wants to push their local code. It helps in creating connections with other repositories.
```
Example:- git remote add origin <git repo url>
```
![7(a)  git remote add origin url](https://user-images.githubusercontent.com/89749940/196074246-36b2f06c-371c-4d46-9ef2-c2c612d1e778.png)

b) git remote -v - To list the remote connection user has to other repositories.
```
Example:- git remote -v
```
![7(b)  git remote -v](https://user-images.githubusercontent.com/89749940/196074264-fcb251df-0011-4cdd-be13-1677cdf605f4.png)

### 8. push - To push the branch or to push the changes in the branch to the GitHub repo.
```
Example:- git push origin main
```
![8  git push origin main](https://user-images.githubusercontent.com/89749940/196074277-7abc2f93-dbd0-4f84-865f-05d0103a9720.png)

### 9. log - To display all the commits in a repository's history.
```
Example:- git log
```
![9  git log](https://user-images.githubusercontent.com/89749940/196074304-f4f153b9-3de0-4393-9d01-d8181e16e671.png)

### 10. merge - To merge the current branch into the specified branch (main).
```
Example:- git merge
```
![10  git merge](https://user-images.githubusercontent.com/89749940/196074318-db78bf30-9ce8-47a8-a073-db03fb73610b.png)

NOTE - we are on the developer1 branch so to merge we have to checkout in the main branch than only we are able to merge onto main.

![10(Note)  git merge](https://user-images.githubusercontent.com/89749940/196074361-1fa1a104-62be-47fd-b543-904b2cb6e398.png)

### 11. restore - To unstage or even discard uncommitted local changes.

### 12. reset - To undo the recent changes that are to be committed.

### 13. stash - To take your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy

### 14. clone - To point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.

### 15. pull - To pull the new changes from git repository to local machine.

### 16.
