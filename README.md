### Get Help Details
git help config

### git config --global user.name "Dibsyhex"

### initialize an empty repo
git init

to see the status of the repo
git status

add a file

git add file1.txt

add a file to staging area

git commit -m "My first commit"

git add dir1/

git log

git diff

git diff --stage

git reset HEAD a.txt

Skip staging and add. Add changes from all staged files. Dosent add untraced files
git commit -a -m "commit without staging"

Incase we forgot to add something to the commit and want to ammend to the same comit , add it first

git add

git commit --amend -m "Message" Change the last commit

Undo last commit and put evertything to staging
git reset --soft HEAD^ [ the ^ symbol meand move to one commit before HEAD ]

git reset --hard HEAD^ undo last commit and all changes

git remote add origin http://xyz.git

pushing to remote "repo name" , "local branch to push"
git push -u origin master 

