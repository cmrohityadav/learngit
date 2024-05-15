# Learn about git and gihub
hello world
```javascript
console.log("hello")
```



### To start git software 
#### once per project
```
git init
```

### To Check the status
```
git status   
```
### ADD
#### . is used to track the all files
```
git add  files1.extension file2.extension
git add . 

```

### commit
```
git commit -m "add your msg"   
```
### log
#### --online is for short 
```
git log  
git log --oneline  
```

### git config
#### all about configuration
```
git config
```
### git config
#### all about configuration
```
git config
```
### git config --global
#### all about configuration --global
```
git config --global
```
### git config user.name
####  This command sets the Git username only for the current repository.
```
git config user.name "username"


```
### git config user.name
####  This command sets the Git username globally.
```

git config --global user.name

```
### git config user.name
#### to set the  user email
```
git config user.email "email"
git config  --global user.email "email"
```
### get all detail of config
#### use only in root dir of system
```
cat .gitconfig
```

###  check the branch
#### 
```
git branch
 ```
###  To create new brnach
#### 
```
git branch nav-bar
 ```
###  To switch the branch
#### 
```
git checkout nav-bar
git switch master
 ```
###  To merge the branch
#### 
```
git merge nav-bar
 ```
###  To delete the branch
#### 
```
git branch -d nav-bar
 ```
### to  create new brnach and switch to it
#### 
```
git checkout -b footer
 ```
### to  differentiate
#### '---' is First file and '+++' be second file
```
git diff --staged
git diff branch1 branch2
git diff commitid1 commitid2
 ```
### stash
#### 
```
git stash
 ```
### stash
#### 
```
git stash pop
 ```
### stash
#### 
```
git stash list
 ```
### stash
#### 
```
git stash apply stash@{n}
 ```
### move to at some timeline
#### 
```
 git checkout 4201c93
 ```

### 

