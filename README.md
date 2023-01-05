# forkme

# Contributor 

## Clone forked branch
git clone "https://github.com/amarinhub/forkme"

## Add github source (origin forked branch)
git remote add source https://github.com/mcmdothub/forkme

## Start development
git reset --hard source/master

## Create new branch
git checkout -b "feature/adrian"

## Add your changes
git add --all
 
## Commit changes
git commit -am "changes feature/adrian"

## Push changes
git push

## Update master branch from Source master
git pull source master

git merge source/master master

git push
