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

# branches
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
- display commits in the project
git log
git log --online
git log --graph
# merge
- types of merge
1- Fast-Forward merge
2- true merge 
there is conflict
# tag
- display tags in the project
git tag
- create tag in project
git tag tag-name
- display tag details
git show tag-name
- delete tag 
git tag -d tag-name
# git cloning
git clone link
- upload local files or modified files to github
git push
- download files or modified files from github
git pull

