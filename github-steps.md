#  Welcome at git steps

## 1- sign in to github
---
## 2- edit your profile
---
## 3- Follow The Command Steps
---

### step 1 > add a new remote repository on github same name of your local project 

### step 2 > link local repository with the remote repository
> chick your remote connections
```
git remote -v
```




```
git remote add origin https://github.com/MohamedMamdouhMorsi/git-github-help.git

```
> push your project to remote
## you can push your work in the ( main )  branch on the github wich will changed or you can push your ( master ) branch what you devoleped on your local repository that will keep both of them  and the (main) branch will keep the default version of github basic branch  

```
git branch -M main 
git push -u origin main
```

> pull  = get your project from the remote repository 

```
git pull origin main     
```  

## To Save Your Exist Work Use Stach 
```

git add .

git stash

git pull 

git stash apply 
```
### (((   or whatever your branch name   )))

### i think we Done !! 