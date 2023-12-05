# DAY 1 

## INTRODUCTION TO LINUX COMMANDS

- `cd directory_name` - change directory

- `cd ..` - go back to previous directory

- `ls` - list files in current directory

- `ls -l` - list files in current directory in long format

- `ls -a` - list all files in current directory including hidden files

- `mkdir directory_name` - create a directory

- `rm file_name` - remove a file

- `rm -r directory_name` - remove a directory

- `rm -rf directory_name` - remove a directory forcefully

- `touch file_name` - create a file

- `cat file_name` - display contents of a file

- `cat file1 file2` - display contents of multiple files

- `cat > file_name` - create a file and write contents to it


### NEEDS SUDO PERMISSION

- `chmod role=permission file_name` - change permissions of a file (generally in the format of rwx where r=read, w=write, x=execute)

- `chown user_role file_name` - change ownership of a file

- `chown user_name:group_name file_name` - change ownership of a file

- `chgrp group_name file_name` - change group ownership of a file


## INTRODUCTION TO GIT AND GITHUB

### CONFIGURING USER ON LOCAL MACHINE

- `git config --global user.name "user_name"` - set user name
- `git config --global user.email "user_email"` - set user email

### BASIC GIT COMMANDS

- `git clone remote_repository_url` - clone a remote repository to local machine

- `git init` - initialize a git repository
  
- `git add file_name` - add a file to staging area

- `git add .` - add all files to staging area

- `git commit -m "commit message"` - commit changes to local repository

- `git remote add origin remote_repository_url` - add a remote repository

- `git push -u origin master` - push changes to remote repository

- `git pull origin master` - pull changes from remote repository

- `git status` - check status of git repository

- `git log` - check commit history

- `git branch branch_name` - create a new branch

- `git checkout branch_name` - switch to a branch

- `git checkout -b branch_name` - create a new branch and switch to it

- `git merge branch_name` - merge a branch to master branch

- `git branch -d branch_name` - delete a branch
