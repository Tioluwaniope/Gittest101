# skill_skule_Gittest101  
## Training to introduce the cohort on how to push from the local environment to Github  
- Downloaded Gitbash (https://git-scm.com/downloads)  
## configure gitbash  
- git config --global user.name "tolulope"
- git config --global user.email "adeleketolulope491@gmail.com"
  # prepeare the configured environment
- mkdir website
- cd website
- git init
- touch index.html
  ## clone your github repository
- git remote add origin <url> (this should be the url from your created repo-use https)
  ## push to Github
- git status ( To check your git status as regards to the staging area)
- git add index.html
- git commit -m "create index.html
- git push origin master
