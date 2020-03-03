## 
add a line
### 1. Getting started with the basic command line

Open a terminal window and try the basic commands.

`pwd` - Print working directory, will return the current directory you are looking at. 

`ls` - Tells you what files are folders are in your current directory.

`cd` - Change directory, will go to a relative or absolute path directory.

`touch <filename>` - This creates a blank file named and located in the first argument. 

### 2. Initializing a new repository: git init

`cd/path/to/your/existing/project`

`git init`


### 3. Cloning an existing repository: git clone

`git clone <repo url>`

### 4. "edit-add-commit-push"cycle 

Change directories to /path/to/project

`cd/path/to/project`

Create a new file test.txt in project

Saving changes to the repository: git add and git commit

`git add test.txt`

`git commit -m "added test.txt to the repo"`

Repo-to-repo collaboration: git push

`git push`

### 5. Basic git commands

`git pull <remote>`

`git pull --rebase`

`git pull <remote> <branch-name>` - Download changes and directly merge/integrate.

`git fectch`

`git merge`

`git add .` - Add all current changes to the staging area

`git add <filename>` - 

`git commit -m "add comments"`- The `-m` flag expects to be followed by a commit message surrounded by quotes.

`git commit` - Commit previously staged changes.

`git commit -a` - Commit all local changes in tracked files to the staging area, ready for the next commit.

`git push`

`git push <remote> <branch-name>` - Publish local changes to the remote repo.

`git push origin master` - Push your master branch to your origin server

`git init` - Create a new local repository

`git clone` - Get a copy of an existing Git repository

`git status` - Lists every file that has changed since the last commit, and files currently staged for commit

`git diff` - Lists every individual change to every file that has changed since the last commit. Add the '--staged' tag to show changes currently staged for committing.

[test link](https://github.com/ypff/new-test/blob/master/untitled.md)

