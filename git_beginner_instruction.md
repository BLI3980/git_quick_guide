>**This is ia quick user guide for beginners to basics of Git. It is a live document and it being updated regularly**
<p> </p>

# About Git



# Download and install



# Start

## Create and open project folder



## Initialize



# Begin to work

## Create files and start working on project



## Checking status or work


   
## Branches - create, delete, merge, move between

Branch is a feature which allows you to work on different areas of project independently. For instance, you might want to continue main work on the project while at the same time develop a feature of the project which, if succeeds, will be merged with main project in future.

![Branches](branches.jpg)

Here are the commmands that can be used for branches:
|Command| Desciption|
|----------|-----------|
|git branch| - Displays the list of currently existing branches. And also highlights the branch in which you currently reside with green color and a star symbol
|git branch < branch name >| - Create new branch with < branch name >
|git branch -d < branch name >| - Delete an existing branch. Use small -d perferably. This way deleting will be performed only if all work in the branch is already merged with another branch
|git checkout < branch or commit hash >| - Move to the specified branch
|git checkout -b < branch name >| - Create new branch and move to it, in one command


## Merge branches
|Command| Desciption|
|----------|-----------|
|git merge < branch name >| - Merge a branch in which you currently reside with a branch you specify. I.e. merge to be done from a branch *into* which merge will be done. For instance, if you want merged information to be in branch "a", then make sure you are in this branch and then type "git merge branch b"


|Command| Desciption|
|----------|-----------|
|git status| Checks the status
|git add < file_name >| Stages a file for next commit
|git add .| 
|git commit -m "< comment >"|
|git commit -am "< comment >"|
|git log|
|git diff ##|
|git diff < commit "a" hash > < commit "b" hash >|
|clear|
|git branch|
|git branch < branch name >|
|git branch -d < branch name >| **small d**
|git checkout < branch or commit hash >|
|git checkout -b < branch name >|
|git merge < branch name >| merge to be done from branch *into* which merge will be done. For instance, if you want merged information to be in branch "a", then make sure you are in this branch and then type merge

