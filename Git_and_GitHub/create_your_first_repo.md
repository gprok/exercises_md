# Create your first repository

## Install Git and open an account on GitHub

If you have a Mac or Linux, git is already there.   
In Windows, download git from: https://git-scm.com/   
Installation is straightforward. Two things to check:  
1. Some step asks if git should be in PATH. Select this one
1. Another step asks if you want **master** or **main** as the default branch. Select **main**.

## Create a GitHub repository

1. Go to GitHub and click the green button **New**
1. Give a name to your porject. e.g. ```my_project```
1. In the page that appears you will need the url that is been created. e.g. https://github.com/your_account/my_project.git

## Create a local project

Before using Git for the first time configure user name and email   
```git config --global user.name "Your Name"```   
```git config --global user.email "youremail@yourdomain.com"```

1. Create a folder, e.g. ```my_project```
1. Open the folder into Visual Studio Code and create one or more files. Any type of files will do (maybe create .java files)
1. Open the Visual Studio Code terminal
1. Initialize git in the folder: ```git init```
1. Connect to the remote project: ```git remote add origin https://github.com/your_account/my_project.git``` (of course put your own URL at the end)
1. Check current changes: ```git status -s```
1. Add changes to be included in next commit: ```git add --all```
1. Commit: ```git commit -m "a meaningful message here"```
1. Upload to GitHub: ```git push -u origin main``` (if you selected master as the default branch, chance main to master)
