mit netlify deployen
git init
git add .
git commit -m "test"

auf github > new repo
git remote add origin [git@github.com:QD2022/deploy-netlify.git]
git push -u origin master

on netlify >
import existing repository
connect to git provider
pick a repository
deploy site
change domain name in settings