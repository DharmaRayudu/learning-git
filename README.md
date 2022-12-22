# learning-git

# This repo for learning git commands. 

To create a folder in current directory
mkdir <folder_name>

--Current working directory--
To create a files
touch index.html(This can be any files)

To add all the files to git stage
git add -A
or
git add . 

To revert back added files from stage
git rm --cached <file_name>
git rm -r --cached . -> This will unstage all the files 


--Moving to commit area--

From staging area to Commit Area
git commit -m "Any message" -> This will move files from staging to commit history

After commiting if you want to see the changes. 
git show <commit_point>

Any modificate you want to restore
git restore <file_name>

To modify files
vi index.js
after this enter I -> here you can insert some thing
After that press escape-> :wq

To see change you done above
cat index.js

Amend:
git commit --amend -m "body added in main.css" -> This will update the last commit message


--Moving to Repository--
git push 
git pull


--Cretae abranch --
git branch <branch_name> -> This will create a new branch

git checkout <branch_name> This will switch to that branch
git switch <branch_name> Same like above command.
git switch -c <branch_name> This will create a new branch and switch to that. 
git checkout -b <branch_name> This will also create a new branch. 

git branch -d <branch_name> This will delete the branch


To switch previous branch and current branch
git checkout -

--Rebase
git pull -r origin master 

gitpod



