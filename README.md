This file is for referring basic commands and pushing files into Remote repository.

git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:Prathamesh-dbg/Git-Tutorials.git
git push -u origin master

git remote add origin git@github.com:Prathamesh-dbg/Git-Tutorials.git
git branch -M master
git push -u origin master

//Delete branch from local repo
git branch -d <branch_name>

// Delete branch from the Remote repo
git push origin --delete login-system
