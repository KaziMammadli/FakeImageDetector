Create a github account
Download git 
Open the downloaded git file
Accept everything, push next buttons, checkmark the launch git bash box.
Now you see a window like cmd, after that write following:
1.Step: git config –global user.name “Kazim Mammadli” press enter ( You should enter your name)
2.Step: git config –global user.email kazimammadli@gmail.com  press enter( you should enter your email)
3.Step: git config –global init.default branch main  press enter 
Additional info : ( if you need any help related these commands, write: git help config)
4.Step: cd :/users/kevin/….  press enter
5.Step: git init press enter
6.Step (track files): git add filename press enter or git add . ( tracking all file in folder)
7.Step: git commit -m “first commit -  committing all files to the repository”press enter

If you have made changes to the file, type “ git status” to see what is changed, and to see the difference type “git diff”.If you are satisfied with differences type “git add filename”.

If you want to remove a file from staging type “git restore –staged filename”

To see the all commits type “git log”, if you want to see all commits in one line type “git log –oneline”

To change previous commit type :git commit -m “Changed file name to smth” – amend

To jump previous commit type “git reset (tag of commit)”

To commit the change in the branch, type “git commit  -a -m “updatsdkfajdk”

BRANCH operations:
We have main branch and other created branches, if we want to test smth, we test it on the created branches, then apply the change to the main.
Creating a branch, type “git branch (branchname)”

Seeing all branches, type “git branch”

Switching branch, type “git switch (branchname)”

Merging branch to the main, type “git merge -m “merge to main” (branchname)

Deleting branch, type “git branch -d (branchname)” 

Github part:
After creating a repository, it gives us instructions to upload our folder to GitHub. After doing all the steps, 
Download Change in github to your local computer, type “git pull”





