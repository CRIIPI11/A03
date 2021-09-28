#Assignment 03

##Directions on Using Git and Github

To start off, we first need to know the simple difference between Git and GitHub. Git is a software use to track
any changes made to a set of files, and GitHub is a provider of internet where a developer uploads and keeps record of those changes.
The first step on using Git and GitHub is to install Git on the user's computer using the following link, https://git-scm.com/downloads.(During the installation process, make sure to install Git Bash)
After installing Git we can proceed to open Git Bash or the terminal of our preference, here we can start by connecting our local
Git with our GitHub account. Once this is done, we can navigate to our work folder and use the command "git init" to start a git repository.
Once the git repository has been initiated, we can start working on our files. After finish working, we can go to the terminal and input
the command "git add" to add all the changes to the staging area. Then we can input the command "git commit -m '<commmit message>'",
this will capture the changes made to the files at this point of time and keep the record.(on the '<commmit message>', this is where
you will write a brief explanation of the changes.) On GitHub, create a new repository, and once created connect your local repository
to your remote one git the command "git remote add" on your terminal. Once connected, input the command "git push <remote>" to send the
capture to GitHub. You will receive a pull request notification, click on it, and it will open a pull request. Here you can see all the
commits made to the files, as well as having the option to make comments and check if your changes are able to merge to the repository on GitHub.
Once everything is good, you can go ahead and merge the changes, this will update the repository on GitHub with all the changes you made,
making it available for you or your team.
