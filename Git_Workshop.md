# Git Workshop
## Introduction 
Git and GitHub are different technologies that can help you do version control which essentially means keep track of different versions of code, or changes you have made to programs you are working on.

So, we'll first start off with introducing what Git and GitHub really are, and how they can be leveraged for projects you or your teammates are working on. Then we'll take a look at the command line interface Git offers.

**What is Git**  
So, one of the core features of Git is that it helps you keep track of changes you have made to your code. For example, if I had a computer program that has a few lines of code, as I add or delete lines, Git can help track the changes I have made across the different versions of my program such that at any point in time, I can go back through this different versions of my program to see what it looked like at a point in time or see what changes I have made. 


## Commands
**git init `folder-name`**  
Git init is basically the first step to initialize a git repository. A git repository basically refers to a set of code whose changes are tracked via Git. So, if we go ahead and move into the directory, and run `ls`, you wouldn't see much. But if we go ahead and run `ls -a`, you'll see the `.git` folder. The `.git` folder


**git config `options`**
* changes git configuration

**git add `file`**  
* adds a file to the staging area
* tells git to include a file in the next commit or 'save'
* next revision of the repository will include this file

**git commit -m `message`**
* saves changes to repository as a revision
* records a accompanying message with the commit
* message summarizes changes made

**git reset `option`**
* jumps back to an older commit and discards commit made after the target commit
* `--hard` option specifies a hard reset, which is a reset wherein commits and all your changes made to files will be discarded
* `--soft` option specifies a soft reset, which is a reset wherein commits are discarded, but changes made to files will be preserved

**git branch `new-branch-name`**
* creates a new branch or 'child' from the parent branch
* `-D` option specifies delete, eg. `git branch -D buuuu` deletes the branch named buuuu

**git checkout `branch-name`**
* switches to the branch in the specified `branch-name`
* `-b` specifies create and switch to newly created branch