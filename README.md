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

git branch -a // to show all branches
git branch -d branch
git branch --merged
git branch --no-merged

git merge --abort
git merge branch-name
cat .git/HEAD

#git config
git config --global user.name "<Your-Full-Name>"
git config --global user.email "<your-email-address>"
 
#git pull 
git pull 
git pull origin master
git pull -all 
  
git remote -v 
git push -u origin new_branch
git push origin --delete [branch name]
  
  
  
  
  
  





