BASIC GIT COMMANDS
Git is distributed version-control system for tracking changes in any set of files. 
shakshi ne match harwa diya

git init
This command turns a directory into an empty Git repository.

git init [repository name]

git config
The command sets the author name and email adress respectively to be used with the commits.

git config -global user.name "[name]"

git config -global user.email "[email]"

git add
The following command adds a file to the staging area.

git add [file]

The following command adds one or more to the staging area.

git add *

git commit
This command records or snapshots the file permanently in the version history.

git commit -m "[Type in the commit message]"

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

git command -a

git status
This command returns the current state of the repository.

git status

git branch
To determine which branch the local repository is on, add a branch, or delete a branch.

git branch

git branch [branch name] (Creates a new branch)

git branc -d [branch name] (Deletes the feature branch)

git checkout
To start working in a different branch, use git checkout to switch branches.

git checkout

git merge
Integrate branches together.

git merge [branch name]

git remote
To connect a local repository with a remote repository.

git remote add [variable name] [remote server link]

git clone
To create a local working copy of an existing remote repository.

git clone [url]

git pull
To get the latest version of a repository run git pull.

git pull [Repository Link]

git push
This command sends the committed changes of master branch to your remote repository.

git push [variable name] master

This command sends the branch commits to your remote repository.

git push [variable name] [branch]

This command pushes all branches to your remote repository.

git push -all [variable name]

This command deletes a branch on your remote repository.

git push [variable name] :[branch name]

git rm
This command deletes the file from your working directory and stages the deletion.

git rm [file]

git log
This command is used to list the version history for the current branch.

git log