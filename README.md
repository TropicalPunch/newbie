# newbie
Git Exercise
Before you start your Git based project make sure you config your user.name and user.email:
git config --global user.name "YOUR NAME"
git config --global user.email YOUR@EMAIL.HERE
1. Install git or check version
2. Create a blank folder and open it in Vscode
3. Use git init to init a new git repo in the folder you are working on
4. Add files to the folder
5. Use git status  to check what is going on
6. Use git add . to add all of the new/modified files to the staging environment
7. Run git status again each time you want to make sure an operation had accrued
8. When you are ready to commit your changes run git commit -m "commit message"


add a .gitignore file to include node_modules for example 
Create a new repository at Github.com - please make sure it is empty without any title or extra files.
Follow the instructions to connect your remote repository to your local git repo git remote add origin SOME_URL…
You can inspect the list of remote repositories connected to a local repo by running git remote  or git remote -v
Push your local commits to your remote repo git push origin master
Refresh your Github web page and inspect the files and commits.  
Next - add a readme file to your remote github repo (use the big green button at the bottom to do it…)
Modify your local repo, make some changes and commit them locally
If you’ll try to push them using git push origin master you will get an error since your remote repo contain changes that your local repo doesn’t. So before pushing changes to a remote repo, you usually want to pull the latest changes. run git pull origin master
The pull operation will create a new commit locally you can inspect with git log --oneline
Finally you can push your commits to your remote repository by running git push origin master
