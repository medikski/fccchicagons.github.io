#github collaboration

#to make a new branch: git checkout -b branch-name-here

#to switch between branches:
git checkout branch-name-here

#to see what branch you're on
git branch

#to add changes and commit
git add .
git commit -m "short description of what you did here"

#to push changes made in branch to remote repository, first return to master branch, next add in the branch name after git push origin:
git push origin branch-name-here
