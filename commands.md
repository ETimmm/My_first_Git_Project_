# Commands

## Basic routine

checking if files were comitted with git status 

`git status`

adding to staging area

`git add <file name> <file_name>`

adding to local repository

`git commit -m "meaningfull message"`

bridging between local and remote location

`git remote add origin https://github.com/ETimmm/My_first_Git_Project_.git`

note: problems with authentication were solved by creating a new ssh key (removed the previous one)

Sync commands

`git pull`
`git push`


revert command when you have a wrong commit

`git revert`

cloning an existing repository - including the bridge

`git clone`

rewrite last commit message

`git commit -amend`

list the name of the bridge

`git remote`

delete the bridge from local to remote, list bridge first using git remote (above)

`git remote remove <name>`

create a branch

`git branch <name>`

move into the branch

`git checkout <branch_name>`

 not branch_name = name of branch you want to go to
DD--> I am changing something to induced a conflict
 lets get in trouble
