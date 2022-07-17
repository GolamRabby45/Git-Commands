# Git-Commands

# from local to remote
git init 
git status
git add .
git commit -m "some msg"
git remote add origin main/master
git push -u origin main


# from remote to local
git clone url

# branches
git log --oneline -5 
git branch branch_name
git checkout branch_name 
git checkout -b branch

git diff master..anotherbranch
git help branch
git log --oneline -5 
git log master --oneline -5

git branch -a
git branch -d branch
git branch --merged
git branch --no-merged

git merge --abort
git merge branch-name
cat .git/HEAD






