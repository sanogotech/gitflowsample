#ATTENTION : Il ne faut jamais travailler sur ces deux branches ! Donc pas de commit/push/ develop only !!!

* git init
* touch  README.md
* git add .
* git commit -m "Add README"
* git branch
* git remote add origin  urlrepo
* git flow init
* git branch
* git flow feature start feature1
* touch index.html
* git add *
* git commit -m  "Add index file"
* git flow feature publish feature1
* git branch
* git pull
* git flow feature finish feature1
* git flow release start v0.1
* change readme.md with version
* git add .
* git comit -m "Add version"
* git flow release finish v0.1
* ** retour sur develop
* git branch
* git push --tags  
* git push origin master
* git flow hotfix start bugfix1
* touch  code
* git add .
* git commit -m "code bug fix"
* git flow hotfix publish bugfix1
* git flow hotfix finish bugfix1
** retour sur develop
* git branch
* git push --tags  
* git push origin master
