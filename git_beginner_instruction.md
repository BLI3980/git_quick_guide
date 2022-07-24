>**This is ia quick user guide for beginners to basics of Git.**
<p> </p>

# About
Git is one of the most popular solutions in market for managing the versions of files in complex projects, whether performed by one person or multiple team members. 

A few examples where the control of versions is needed: 

1. You created a website and it works just fine. However, you decide to add some new features to this site. If new feature corrupts the current version of website, you have problems. But if you saved your current version prior to adding new feature and if you can go back to saved version, then you are ok.
2. You completed a work on a big document and you are happy with it. At the last moment you made some changes to the document that you don't like. If you have means to go back to your saved version of document, you don't have to re-write the entire document.
3. There is a shared document in a project to which several members of the project can have simultaneous editing access. To avoid situation where a work of one member uncontrollably supersedes a work of the others, all versions of the document need to be controlled.
<p> </p>

# Download and install

Download and install the latest version of Git use the following link: 
> [Download Git](https://git-scm.com/downloads)
<p> </p>
While it is possible to manage a project through Git interface itself, it is not convenient, that's why there are many other applications that are used as console/terminal for Git. Visual Studio Code is one of the most popular ones.

Download and install the latest version of Git use the following link: 
> [Download Visual Studio Code](https://code.visualstudio.com/download)
<p> </p>

**Note:** It is recommended to install Git first, followed by VSC. 
<p> </p>


# Start
Once Git and VSC are installed, create a folder on your PC or remote location where your project will reside and where your repository will be.

>Avoid using cyrilic letter in a path name to your folder

**Note:** Repository is not exactly the same thing as a folder with project files. Repository is a place where Git performs tracking of all changes in the project and controls them. While it is in the same place as the project folder, it is not created automatically when you create the folder. You need to initiate it using a command.

 - git init - a command that creates a Git repository

Once repository is created, you can start creating files in it and work on them.

At some point after creation of repository the program will ask you to introduce yourself.
Commands that and information that you will need to provide is as follows:
- git config --global user.name < name >
- git config --global user.email < email address >

<p> </p>

|Command| Desciption|
|-----------|-----------|
|git status| Checks the status
|git add <file_name>| Stages a file for next commit
|git add .| 
|git commit -m "<>"|
|git commit -am "<comment>"|
|git log|
|git checkout [<branch>]|
|git diff| 

