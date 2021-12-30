# new-python
<img src="https://pbs.twimg.com/media/Et8Nx58XcAIqGxS.png" width="100" height="100"/>

git init

git remote add origin https://github.com/sandra-girgis/new-python.git

git add .

git commit -m "new file" .

git push origin master

git checkout -b dev

git add .

git commit -m "dev file" .

git push origin dev 

git merge dev   

git checkout -b test 

git add .

git commit -m "test file" .

git push origin test

git checkout master

git merge test

to delete localy 

git branch -d branch_name

to delete remote

git push origin :branch_name

git tag -a v1.7 -m "version 1.7" 

git push origin v1.7

to list tages

git tags

To delete remote tag

git push origin --delete v1.7

To delete local tags

git tag -d v1.7
