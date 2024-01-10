# github-3.1-mingzi

## Git Commands

1. git config
``` sh 
git config -global user.name "<NAME>"
git config -global user.emal "<EMAIL>"
```
this command sets author name and email address respectively to be used with your commits

2. git init
```git init <REPO_NAME>```
this command used to start a new repository

3. git clone
```git clone <URL>```
This command is used to obtain a repository from an existing URL

4. git add
```git add <FILE_NAME>```
This command adds a  file to the staging area, use . to select all files in the folder

5. git commit
```git commit -m "MESSAGE"```
This command records or snapshots the file permanently in teh version history

6. git diff
This command shows file differences which are not yet staged

7. git status
This command lists all the files that have to be commited

8. git branch
This command lists all the local branches in the current repository

9. git checkout
```sh
git checkout <BRANCH_NAME>
git checkout -b <BRANCH_NAME>
```