# git_lab_3
second lab
Scenario: You have completed your work on a feature branch and want to merge it into the main branch. Create a pull request on GitHub. Please note, you need to push feature branch from local to remote repository and then raise pull request on GitHub to merge the changes on the main branch.

Step 1 : clone the remote repository 
1) git clone "git@github.com:SVS2495/git_lab_3.git"

Step 2 : create the feature branch and complete your work
1) git checkout -b feature1
2) updated food.txt file and commited the changes

Step 3 : file is ready to merge with main branch
1) aviod conflicts : git branch main
2) git pull origin main
3) git branch feature1
4) git merge main

Step 4: file is ready to merge with main (local)
1) git branch main
2) git merge feature1

Step 4: push feature1 branch to remote repo
1) git checkout feature1
2) git push origin feature1

Step 5 : create pull request from github
1) create pull request from "compare and pull" tab
2) then after comparing merge it with main branch 
