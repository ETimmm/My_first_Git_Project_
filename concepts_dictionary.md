# Dictionary of concepts

## Differentiating

- Git: Software/tool to track changes in files and folders

- Github: A navigator. A backup of your timeline/git repository.

## Conceptual areas

1. Developing area: My folder where I will develop my project.

2. Staging area: after adding (git add), a change is added to this stage, ready to commit 

3. Local repository: my .git file where git software is managing all the versions I commit to.

4. An explenantion is mandatory when committing.

## From local to remote 

- ssh key: A way to securely connect to a remote computer/location/server. We add it to GitHub in the setting for ssh key

- How to create an empty remote repository from Github: add a new repsitory on github, give it a nice name . dont add any files. follow the instructions to connect with the local 

- creating the bridge between local and remote Github repository by using command. Do this only when you have a new project/repository

- i should always sync the changes. Git push when you want to put everything that is committed online. Git pull when you want to retrieve changes from online to local folder. So when youstart working locally always start with git pull (in case update happend by collaborator)

- in case you want to get a new repository/when your repository went bad/empty, use git clone to retrieve from the remote github loacation

## Branching

A branch is an Alternative history, with at least 1 shaired point (commit) in time with the main, to test different possible solutions to the problem.
A branch has an independent history (log)
Make sure to give it a name

All collaborators should work in his own branch, not in the main.
The best solutions goes to the main branch.

WHen creating a loose head, you can create branch name and connect it to the tree by using switch -c command. otherwise this input is not saved.

# TAGGING and RELEASES

Tagging = Highlight good versions (commits /states) => special name or version name for a point in time that is important to you = TAG, for example a spot which is good, and you can go back to later easily
new change on concepts