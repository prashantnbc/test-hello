# test-hello
test repo

# this file also tell about using git from command prompt

echo "# test-hello" >> README.md
#Step#1- run these command run from git command prompt
git init
git add README.md
git commit -m "first commit"

#step#2  - login in Github and create repository test-hello

#step#3 - to connect from git terminal/cmd-prompt to Github or remote repository
#comment - To see which remote servers you have configured, you can run the git remote command
git remote -v
#origin is a name to remote - generally to server url with master branch
#now actual command to tell local repo that what remote it belongs to 

git remote add origin https://github.com/prashantnbc/githelp.git

# Step#4 - push content from local to remote named "origin" master branch
#this will ask you the UserName and Pwd for Github
git push -u origin master

# Step#5  you can pull content from master branch
git pull

# example ...or create a new repository on the command line

echo "# githelp" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/prashantnbc/githelp.git

git push -u origin master

# or push an existing repository from the command line

git remote add origin https://github.com/prashantnbc/githelp.git

git push -u origin master
