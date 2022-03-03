# github-commands
all the commands that are frequently used with it's function

## GETTING AND CREATING PROJECTS

*  git init               - Initialize a local Git repository
*  git clone ssh://git@github.com/[username]/[repository-name].git - Create a local copy of a remote repository


## Basic Snapshotting
* git status - check status
* git add [filename.txt] - add a file to a statging area
* git add -A - add all new and changed files to the statging area
* git commit -m "[commit massage]" - commit changes
* git rm -r [filename.txt] - remove a file(or folder)

## Branching and merging
* git branch - list branches
* git branch -a - list all branches
* git branch [branch name] - create a new branch
* git branch -d [branch name] - delete a branch
* git push origin --delete [branch name] - delete a remote branch
* git checkout -b [branch name] - create a new branch and switch to it
* git checkout -b [branch name] origin/[branch name] - clone a remote branch and switch to it
* git branch -m [old branch name] [new branch name] - rename a local branch
* 
