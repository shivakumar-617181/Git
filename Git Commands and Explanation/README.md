→ **git init .**

It will Initializes the empty git local repository in current Directory/folder.

**→ git add .**

Adds all changes (new files, modified files, and deleted files) in the current directory and its subdirectories to the staging area from Working Area.

Eg: git add *.java → It will adds only java files to staging area in the present working area.

**→ git Commit**

This Command is used to move the files from staging area to local repository.
It is also includes the commit message for the identification purpose.
Eg. Command:- git commit -m "updated variables files"

→ **git status**

This command will shows the status of our work like how many files are in working area, staging area and how many files are to be commit to local repository.

**→ git config --global username “<git global username>”**

This command is used to configure our global user name with git hub username globally.

**→ git config --global email “<git global mail address>”**

This command is used to configure user mail with git hub Mail ID of global mail configuration.

**→ git remote add <alias name> “<git repo URL>”**

This command is used to add our remote repository details with respect our local repository.
alias name = we can take any alias name,
git repo URL = our remote remote URL.

**→ git push <alias name> <branch name>**

This Command is used to push our local repository changes to remote repository.
Syntax:- git push <alias name> <branch name> Pushes the specfic branch name

**git push <alias name> -- all**

It will pushes the all branches to remote repository.

**→ git remote -v**

To know our local repository is pointed to which Remote Repository.

**→ git commit -a -m “<commit message>”**

This command is used to commit our changes to local repository. with touching the staging area.
Note: It will works only for the updated files. not the newly created files in the working area.

**→ git clean**

It will cleans the working area.
Note: It will deletes only the newly created files only but not the updated files.

**→ git reset**


If any files are moved to Staging area mistakenly from Working area, if we want to bring them back to working area then we will use the git reset command

**→ git revert <commit id>**


This command is used to undo our of Previous commit.

**→ .git ignore**

The .gitignore file tells Git which files or directories to ignore in a project. That means Git will not track changes to those files, nor include them in commits.

**→ git branch**

It will shows in which branch we are currently in

**→ git checkout <branch name>**

To change the branch from one branch to another branch.

**→ git checkout -b <branch name>**


It will create the branch and switches into the new branch.

**→ git merge**


It is used to merge the branch. With Currently Checkedout Branch.

**→ git diff**

It is used to differentiate between the branches

**→ git branch -d <branch name>**

It is used to delete the branch

**→ git branch -r**

It will deplays the remote repository branches

**→ git branch -a**

It will displays the all branches which are in both local and remote repository

**→ git log**

it will shows the logs i.e., what are the commits/changes are happened to the current branch

**→ git stash**

The git stash command is used to temporarily save changes in your working directory that you did not committed yet to local repository.

**→ git stash list**

It will list all the stash list (temporary saving of our local repository).

**→ git stash apply**

It will apply the changes of the stash to the working area code. you can apply the particular stash number to working area.
git stash apply stash @{2}

**→ git stash drop**

The command git stash drop is used to delete a stash from your stash list.

**→ git stash drop@{n}**

This Command git stash drop is used to delete a specific stash entry from your stash list. “n” means stash number which will be displayed if executed the git stash list.

**→ git cherry pick**

The git cherry pick command is used to apply a specific commit from one branch onto another, without merging the full branch history.

**→ git clone**

git clone is used to clone/downloading the code to our local machine storage.

**→ git pull**

This command the pulls the remote repository code to directly working area.

**→ git fetch**

This command is used to fetch the code from the remote repository to local repository. if you want to merge the same code with our working area then we can use the git merge command

**→ git rebase**

This command is used to merge the current branch code to another branch with all previous commits to new branch code. i.e., it will maintains the all commits of the previous branch to new branch commits. 
If We use merge all the previous commits will lost (or it will takes) as a single commit.
