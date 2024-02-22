# changed the name of the branch
git branch -M main 

# add file to git
git add ./file.md

# commits the changes to loacl git repo
git commit -m "added file.md"

# make sure to add your username and email if asked
git config --global user.email "luis.b.alvarez1@gmail.com"
git config --global user.name  "Lou Alvarez"
~/.gitconfig

# make sure that the default branch for any repo is main instead of master
git config --globacl unit.defaultbranch main

# create and switch to new branch
git checkout -b branch1

# one more change to show new branch path

# to change branches
git checkout branchname

# merge branches to main --ensure we are on the main branch
git merge branch1