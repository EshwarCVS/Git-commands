# Git-commands

Open Git Bash Terminal

//Get to the required directory and enter the following commands.

git init    // To initialize git

git clone <URL>   //To clone any project

git status    // To know which file is in which state use the following command and to knonw changes that are not staged for commit

git diff -- staged    //To compare staged changes to last commit

git add <filename>    // To add file
  
git checkout

git checkout -b branch

git reset

git diff    //To know all the unstaged changes in the files from the last commit

git checkout package.json

git fetch    //To fetch the information that a person has you dont

git remote add origin git@bitbucket.org:[user]/[my-repo].git

git remote    //To know which remote server you have configured

git add .     //(can use 'git add' or 'git commit -a')

git commit -m "Type your message"

git push -u origin branch   //When you want to push your repo upstream

git rm    // To remove files from your directory

git log   // To know the log entries

When there are any works done locally :

git pull --rebase origin master

git push origin master
