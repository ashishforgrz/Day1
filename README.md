# 17-05-2022

git config-
                                                                       -      git config –global user.name “[name]”
                                                                       -      git config –global user.email “[email address]”      
Git Clone -
git clone <repo name>                                                  -      Creating clone of particular repository

Git Branch - 
git branch <branch name>                                               -      Creating new branch
git branch -d <branch name>                                            -      Deleting a branch

Git Stash - 
git stash save                                                         -      temporarily stores all the modified tracked files
 
Git Log -
git log                                                                -      list the version history for the current branch
Git Checkout -
git checkout <name-of-my-branch>                                       -      Switch to this branch
git checkout -b <name-of-your-branch>                                  -      Make a new branch and switch to that branch

Git Status -
git status                                                             -      gather information

Till now we haven't added the changes that we did in our file.
We will save the changes using git add command

Git Add -
git add -A                                                             -      To add everything at once
git add <filename>                                                     -      Add a particular file

Git Commit -
git commit -m "commit message"                                         -      Commit a change locally with a message

After this you need to push the changes to the remote repository........

git push <remote> <branch-name>                                        -      If the branch is not newly created
git push --set-upstream <remote> <name-of-your-branch>                 -      for newly created branches

Git Pull-
The git pull command is used to get updates from the remote repo
git pull <remote>

Git Reset -
git reset [file]                                                       -     command unstages the file, but it preserves the file contents
Git rm - 
git rm [file]                                                          -     deletes the file from your working directory and stages the deletion     
  
Git revert -
git log -- oneline                                                     -      This is used to see our commit history
git revert <commit code>                                               -      Reset the changes that has been done

Git Merge -
git merge <branch-name>                                                -      merge your branch to the parent branch


Before merging your branch you need to make sure that you are on that particular branch - 
Eg-
First you should switch to the dev branch:

git checkout dev
Before merging, you should update your local dev branch:

git fetch
Finally, you can merge your feature branch into dev:

git merge <branch-name>
