# Demo 

Git Basics readme file.

Going to learn different git commands in detail.

## Subheader

Adding content from local repo.

# Description

Adding description from feature branch. 


# Commands i performed from this tutorial.

git config --global user.name "...."
git config --global user.email "...."
git checkout -b feature-testing
git branch
Made some changes from feature branch and commited.
git commit -am "Changes made from feature branch"
git checkout main
git diff feature-testing 
q to exit
git checkout feature-testing 
git push -u origin feature-testing 
From github , checked the diff and merge the PR (Pull request)
git checkout main
git pull 
git branch -D feature-testing

For merge conflicts : 

git checkout -b testbranch
added some changes
git diff
git commit -am "changes in index from testbranch"
git checkout main
made some changes from main
git commit -am "changes in index from main"
git checkout testbranch
git diff main
git merge main
checked the code from vs code, solved conflicts saved, staged , again commited : git commit -am "solved merge conflicts"
Done.

git remote add origin urlgithub.com
git checkout main
git push origin main
git checkout testbranch
git push origin testbranch
git fetch
git checkout main
git pull origin main
git log --all --graph

