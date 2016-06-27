Git tutorial

Create User:
git config --global user.name "Your name"    -- configure git to user
git config --global user.email "bucy@pornhub.gov"  -- example
git config --list           -- list all the settings
git config user.email       -- check current setting



Manuever in Git: ( BASH TERMINAL ) 

pwd *enter   -- see directory
cd ~ *enter  -- change to home
cd .. *enter -- go back 1 directory
cd /Directory * enter  -- change to the directory
ls             -- list
ls -la         -- list hidden files
clear          -- clear screen
git help       -- list help options
git help option  -- more info on command
git rm third.txt  -- remove file from repository and working copy
git mv file.txt rename.txt   -- rename file



CREATE Clone REPOSITORY:

git clone <url>  << clone the repository on github
git init  << start git project in <directory> folder
git add .   << add all changes to repo
git add second.txt  << add single file
git commit -m "this is our first commit" << takes snapshot from this point and allows to come back with message
git log   << view commit history
git log --author="Bucky"     << See changes from Bucky
git status     << Shows status of all files being kept track of with git.. add and not added
git diff  << tells you how each file is different | Green are changes made to file
git push -u   << pushes code to github

CREATE NEW REPOSITORY:
echo "# Web_Design_Project" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/RafatKhandaker/example_Project.git
git push -u origin master

PUSH EXISTING REPOSITORY:

git remote add origin https://github.com/RafatKhandaker/example_Project.git
git push -u origin master


......... TO BE CONTINUED ............




