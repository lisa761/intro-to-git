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