# Git-learn

[Git branching](https://learngitbranching.js.org/)

To learn git step by step - http://git-school.github.io/visualizing-git/

[Git cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf)

# Git-commands

**Open Git Bash Terminal**

Quick recap of some git commands

- git init    // To initialize git

- git clone <URL>   // To clone any project

- git status    // To know which file is in which state use the following command and to knonw changes that are not staged for commit

- git diff -- staged    // To compare staged changes to last commit

- git add <filename>    // To add file
  
- git checkout

- git checkout -b branch

- git reset

- git diff    // To know all the unstaged changes in the files from the last commit

- git fetch    // To fetch the information that a person has you dont

- git remote add origin git@bitbucket.org:[user]/[my-repo].git

- git remote    // To know which remote server you have configured

- git add .     // (can use 'git add' or 'git commit -a')

- git commit -m "Type your message"

- git push -u origin branch   // To push your repo upstream

- git rm    // To remove files from your directory

- git log   // To know the log entries

** When you have work left in local machine :**
```
git pull --rebase origin master

git push origin master
```
