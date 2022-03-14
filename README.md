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
* git checkout [branch name] - switch to a branch
* git checkout -    : switch to the branch last checkedout
* git checkout --[filename.txt] - discard changes to a file
* git merge [branch] - merge branch into a active branch
* git merge [source branch] [target branch] - merge a brach into target branch
* git stash - stash changes in a dirty working directory
* git stash clear - remove all stashed entries

## Sharing and Updating Projects
* git push origin [branch name] - push a branch to your remote repository
* git push -u origin [branch name] - push changes to remote repository ( and remeber the branch)
* git push - push changes to remote repository ( remembered branch)
* git push origin --delete [branch name] - delete a remote branch
* git pull - update local repo to the newest commit
* git pull origin [branch name] - pull changes from remote repository
* git remote add origin ssh://git@github.com/[username]/[repository-name].git - add a remote repository
* git remote set-url origin ssh://git@github.com/[username]/[repository-name].git - set a repo origin branch to SSH

## Inseption and Comparison
* git log - view changes 
* git log --summary - view changes (detailed)
* git log --online - view changes breifly
* git diff [source branch] [target branch] - preview changes before merging
