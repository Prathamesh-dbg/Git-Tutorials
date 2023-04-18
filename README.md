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

// In order to clone the remote GITHUB website repository into local computer, Use the link for more info --
https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

Go to Code --> HTTPS --> copy link
git bash on computer --> git clone <paste link>
