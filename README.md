Git Learning Node Repository
=

This Repository is to enhance the Git Learning Node Experience. Below you will find the main
workflow pieces that we go over as party of the Learning Node. Please ask your Mentor for 
more information and the documentation if you have not attended or read through the Learning
Node content.

Git's Homepage: https://git-scm.com

Exercises
==

Checking out a New Repository
===
```
git clone git@gogs.caifos.us:Sofiac/git-learning-node.git
```

Creating a New Branch
===
```
git checkout -b firstLast-NewBranch
```

Adding a File to the Remote Server (on a Branch)
===
```
# Create New Directory
mkdir firstLast

# Create the File test.txt
touch test.txt

git add test.txt
git commit -m "Added test.txt"
git push -u origin firstLast-NewBranch
```

Updating your Local Master Branch
===
```
git checkout master
git pull
```

Help! I do not know where I am!
:(
===
```
git status
git status -b

git log
git log --oneline --decorate=full --graph --all

git diff
git diff master
git diff --stat
```
