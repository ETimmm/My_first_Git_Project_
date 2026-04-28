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

## creating branches

create the name of the branch and move into the branch:

```
git branch <branch_name>
git checkout <branch_name>
```
(=multiline code)

or in one line

`git checkout -b <branch_name>`


 to go back to main, git status can be used to see in what timeline you are

  `git checkout main`

  to create the online branch also first, before you can start pushing your new branch


  `git push --set-upstream origin branches_concept`


how to change a branch name 

`git branch -m <new_name>`

# check what collaborator did to my project:

`git pull`
`git branch -a`

will see only main branch wzs pulled. You also have to pull xx_colab branch:

`git checkout xx_colab`

  # merging branches
  
  
  `git merge <branch_name>`   for example a bug fix is done in a branch    branch keeps existing, including the history log , also after merge, including the overlapping timepoints
  
  When there are too many branches: clean up = > delete the branch after the merge
  
  `git branch -d <branch_name>`


 note: branch_name = name of branch you want to go to

to get a list of the local branches

 `git branch --list`

# go back to old commit and start branch from there: 
`git checkout <commit_ID>`

or use git switch, thats when you are typing and actually want to change to a new branch and link it to main
`git switch -c <new branch name>` 