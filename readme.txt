we are learning git here 

#let the community know who you are 
git config --global user.name ""
git config --global user.email ""

#commiting changes 
step 1 make a directory using mkdir
step 2 make a git repo using git init
step 3 write code 
step 4 check status using git status 
step 5 stage the changes using git add 
step 6 commit the changes using git commit -m ""

#checking logs 
git log                           to check the log history
git log --oneline                 for a compact view of the log

#staging and unstaging 
git add filename                  to stage the file
git add .                         stage all the changed files in the current firectory 
git restrore --staged filename    to unstage the file 
git reset HEAD filename           lagacy command for unstagging 


#Branch
git branch                        list of branches that you have created
git branch newbranch              creates new branch

git checout                       older command mostly use with the commit id 
    git checkout branchname       switch to the branch 
    git checkout commitid         switch to the commit id in detached mode

git switch 
    git switch branch name        swicth to branch
    git switch -                  switch back the previous branch 
    git switch -c                 new branch to crate and switch to new branch



Merging 
step 1 switch to the master Branch
step r merge the branch with main branch using command git merge branch name 

git switch master 
git merge branchname 


