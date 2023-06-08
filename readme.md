- display untracked files
git status
<img src="https://github.com/NajlaHamdan/git-command/blob/master/images/git-status.png" width="350"/>

- add files to staged phase "tracked"
git add file-name 
or git add . to add multiple file
<img src="https://github.com/NajlaHamdan/git-command/blob/master/images/git-status-tracked-files.png" width="350"/>

- store files in the reposetory
git commit -m "message"
<img src="https://github.com/NajlaHamdan/git-command/blob/master/images/git-commit.png" width="350"/>
- display branches
git branch
- create new branch 
git branch branch-name
- navigate between branches
git checkout branch-name
- to create new branch and navigate to it in one command
git checkout -b new-branch
- rename brance
git branch -m old-name new-name
- delete branch 
git branch -d branch-name
note we can not delete the current branch to delete it we must check out first and then delete it