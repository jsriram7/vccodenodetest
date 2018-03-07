# vccodenodetest

To switch between local repositories:
git checkout

To branch from a repository and switch local to the local branch
git checkout -b newbranchname existingbranchname

To know which files are to be commited
git status

To add files to commit or stage the commit files
git add -A
git add .

To remove files from commit or unstage the files
git rm filename

To add specific files to commit
git add filename

To commit a file
git commit -m "Commit message"

To push a commit
git push origin branchname

To merge with a particular branch
checkout first into the local branch where you want to merge the code
git merge branchname

Resolve the conflicts. Conflicts are marked by <<<<<HEAD till ======= of your branch to ======== till >>>>>> of incoming branch.
On the IDE, we can choose to keep whatever we want. Either of the two or both.

Once resolved, stage the files, commit and push.

To generate a pull request, go to github and click on the pull request on the branch and generate a pull request to which ever
branch you want the branch to be merged.
Once pull request is sent, wait for its approval.

