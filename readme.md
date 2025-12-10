#learn git and github

##GIT COMMADS

this is git hub commands

#get repo
git clone repo url

#git init
git init
git add .
git commit -m "test"
git status #check status
git branch -M main
git remote add origin url
git remote -v #check remote connection
git push -u origin main #set main as upstream branch for push

#get code
git pull

#git push again
git add .
git commit -m "test"
git push

#git file
.gitignore #add file/folder names for ignore
.gitkeep #keep empty folder track create this file in empty folders

#merge branches
git branch #check brach
git branch branch-name #create new branch
git switch main #switch to main
git switch -c branch-new #switch and create new branch
git checkout branch-new #switch to new brach
git pull origin main #latest pull
git merge branch_name #merge to main
git push origin main #push merged code

