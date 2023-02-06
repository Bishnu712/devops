# devops class 
learning git from github change done

#GIT Commands
git initi: to initialize an empty repository
git clone <repo url>: to clone the remote repo in to local machine
after clonning "cd reponame/directory"
git branch: to check which branch we are working on
git branch -a : to display all the branches
git checkout -b <branch name>: to create a new branch 
Example: git checkout -b my local -branchc

git add -a : to add the file (make the files in to tracking from untracked mode)
git commit -m "commit message": to create the commit (version)
git push origin <branch nae>: to push the local changes to reomte repository for the respective branch 

git pull origin <branch name>: to pull the branch in to current branch

git diff: to see the difference in local machine (this has to be performed before git add)
git status: to check the current status of the files in repo (like, untracked, added, any commits to be made)
git log: to view the commit information 

git push --set-upstream origin <branch name>
