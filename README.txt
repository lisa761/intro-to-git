git reset HEAD file2.txt
to remove the said file from stagin area
Staging are is the one where all the added files are (added yet not commited)

hidden files is made through touch .<name>.<file-type>
this . signifies that it is hidden from git, it still will be visible as a normal file in windows library though

new branch:
git checkout -b <branch_name>
here b flag is to denote its going to be a new branch (or so I think)

switch branch:
git checkout <branch_name>

merge branch:
git merge <branch_name>
usually you want to merge things to master therefore the branch_name here is that of the new features branch whose
features would be added to the master.
we have to be inside master branch to merge into it

delete a branch:
git branch -d <branch_name>
flag d is for delete
ususally not recommended as we shouldn't delete branches unless really neccessary which it never is

// Doesn't work
Connecting to Github:
we first create a remote of the new repositry that we made in github using:
git remote add origin <repo_link>
to check all the remote in out git:
git remote -v
Then to push master into the repositry, we do:
git push -u origin master

========================================================================
YelpCamp token: 5a1900e53135c8732a5dfca4822fa1721518f61d
========================================================================

