# GitFlow-Project

## Playing with git-flow: merge, commits and fun...

## Here step-by-step:

* 1 - creating directory on git
* 2 - creating local directory
* 3 - start git: git init
* 4 - start git flow: git flow init
* 5 - change to master branch: git checkout master (cause when started git flow you are on develop branch to default)
* 6 - git reote add origin hattps://HereYouDirectoryOnGit
* 7 - git push -u origin master
* 8 - git checkout develop
* 9 - Here stating your web app:
  * 9.1 - npm init -y
  * 9.2 - npm install dependencies...
  * 9.3 - all you developed stay here on develop branch
* 10 - git add . 
* 11 - git commit -m "first commit" (inside develop branch)
* 12 - git push -u origin develop
* 13 - git checkout master
* 14 - git merge develop
  * 14.1 - here all your code the same on braches master and develop
  * 14.2 - maybe you want to clone here the best moment
* 15 - continuous development on develop branch (the life goes on dev)
* 16 - git add .
* 17 - git commit -m "second commit development day by bay"
* 18 - git push -u origin develop
  * 18.1 - here your code just on develop branch yet
* 19 - git checkout master
* 20 - git merge develop
* 21 - HERE CREATING HOTFIX BRANCH:
* 22 - git flow hotfix start FOOTER
* 23 - git add . 
* 24 - git commit -m "fix footer"
* 25 - git flow hotfix finish FOOTER
  * 25.1 - here git flow ask you abaut a tag
* 26 - git push
  * 26.1 - here our code go to develop branch
* 27 - git push -u origin develop
* 28 - git checkout master
* 29 - git merge develop
* 30 - git push

### All braches the same, and branch HOTFIX doesn't exist, because you finish them.

## Authors

* **Rogpe** - *Initial work*[

## Flow used

![flow](https://github.com/Rogpe-Prog/GitFlow-Project/blob/master/public/image/flow.png)


