# Git Commands

# To make a repository a git repository
cd repository
git init

# To add origin or head 
git remote add origin https://github.com/username/new_repo
git push -u origin master

# To remove origin or head
git remote rm origin

# To create a new branch
git checkout -b newbranch name

# To check out a branch from git and switch between branches
git checkout master

# To create a new branch(-b) and branch from a repository and switch local to the local branch
git checkout -b newbranchname existingbranchname

# Delete a local branch
1. move to another branch - git checkout master
2. delete the local branch -  git branch -d Test_Branch
2.1 If above command gives you error - The branch 'Test_Branch' is not fully merged. If you are sure you want to delete it and     still you want to delete it, then you can force delete it using -D instead of -d, as:
    git branch -D Test_Branch

# Delete a remote branch
git push origin --delete Test_Branch

# To know which files are to be commited
git status

# To add files to commit or stage the commit files
git add -A
git add .

# To remove files from commit or unstage the files
git rm filename

# To add specific files to commit
git add filename

# To commit a file
git commit -m "Commit message"

# To push a commit
git push origin branchname

# To merge with a particular branch
checkout first into the local branch where you want to merge the code
git merge branchname

# Resolve the conflicts. Conflicts are marked by <<<<<HEAD till ======= of your branch to ======== till >>>>>> of incoming branch.
On the IDE, we can choose to keep whatever we want. Either of the two or both.

Once resolved, stage the files, commit and push.

# To generate a pull request, go to github and click on the pull request on the branch and generate a pull request to which ever
branch you want the branch to be merged.
Once pull request is sent, wait for its approval.

