# gitlab2
#### 1.Create a new project on your local machine,then push it your remote repo.
##### git init
##### git add .
##### git commit -m "add index.html"
##### git remote add origin git@github.com:yossrmohammed/gitlab2.git
##### git push origin master
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q1.png)
#### 2.Create two branches (dev & test) then create one file on each branch, and push this changes to the remote repo.

##### git branch dev
##### git branch test
##### git checkout dev
##### touch style.css
##### git add style.css
##### git commit -m "add style.css from dev branch"
##### git push origin dev
##### clear
##### git checkout test
##### touch index2.html
##### git add index2.html
##### git commit -m "add index2.html from text branch"
##### git push origin test
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q3-a.png)
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q3-b.png)
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q3-c.png)
#### 3.Merge this changes on Master branch and then push it to your remote master branch.
##### git checkout master
##### git merge dev
##### git merge test
##### git push origin master
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q4.png)
#### 4.Tell me how to remove them locally and remotely.
##### git push origin :dev
##### git branch -d dev
##### git push origin :test
##### git branch -d test
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q5.png)
#### 5.Create an annotated tag with tagname (v1.7).
##### git tag -a v1.7 -m "version 1.7"
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q6.png)
#### 6.Push it to the remote repository.
##### git push origin v1.7
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q7.png)
#### 7.Tell me how to list tags.
##### git tag
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q8.png)
#### 8.Tell me how to delete tag locally and remotely.
###### git push origin  --delete v1.7
###### git tag -d v1.7
![UNFOUND](https://github.com/yossrmohammed/gitlab2/blob/master/screenshoots/q9.png)
