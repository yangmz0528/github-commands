# github-3.1-mingzi

## GitHub Authentication
Refer to this link: [GitHub Authentication]
Different modes of authentication:
- username and password with 2FA or passkey
- personal access token
- SSH key

## Git Commands

### git config
``` sh 
git config --global user.name "<NAME>"
git config --global user.email "<EMAIL>"
```
this command sets author name and email address respectively to be used with your commits

### git init
   
```git init <REPO_NAME>```

this command used to start a new repository

### git clone [url]
```git clone <URL>```

This command is used to obtain a repository from an existing URL

### git add [file]
```git add <FILE_NAME>```

This command adds a  file to the staging area, use . to select all files in the folder

### git commit
```git commit -m "MESSAGE"```

This command records or snapshots the file permanently in the version history

### git diff
This command shows file differences which are not yet staged

### git status
This command shows modified files in working directory, staged for your next commit

### git log
This command shows all commits history for the currently active branch

### git branch
This command lists all the local branches in the current repository

### git merge [branch]
This command merge the specified branch's history into the current one

### git checkout
```sh
git checkout <BRANCH_NAME>
git checkout -b <BRANCH_NAME>
```
This command (without -b) is used to switch from one branch to another
while adding the -b will creates a new branch and switch to it

### git push
```sh
 git push <VAR_NAME> master
 git push origin master
 git push --set-upstream origin <BRANCH_NAME>
 ```

 This command sends commited changes of master branch to your remote repository
--set-upstream is to link local branch to remote branch

### git fetch
This command downloads commits, files, and refs from a remote repository into your local repository.
Note: the key difference between git fetch and pull is that git pull copy changes from remote repo directly into your working/local directory while git fetch 

### git pull 
 ```sh
 git pull <REPOSITORY_LINK
 git pull origin <BRANCH_NAME>
 ```
 This command fetches and merges changes on the remote server to your working/local directory

### git remote add [alias] [url]
add a git URL as an alias

[GitHub Authentication]: <https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github#about-authentication-to-github>