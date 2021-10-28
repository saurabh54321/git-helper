# git-helper

# github tutorial 

guid to upload project on github


#### 1 : go to your root dir and open git bash there 

```bash
# intializing repo in local 

$ git init

```
#### 2 : create repository on github

```bash
# 
$ git remote add orgin < repo link >  


# other wise jsut copy and paste given link

```


####  3 : setup main brach 

```bash 

$ git branch -M main 


```



#### 4 : see the track files  

```bash
# to see trackfies <which files are under tracking >

$ git status 


#  to add specific file

$ git add <filename>


# to add all files

$ git add .

```

#### after adding file we need to commit 


```bash 
# for commiting 

$ git commit -m 'massgae'

```

#### after commiting we push code 

```bash 

# push code 

$ git push -u origin main      # to push on main branch

$ git push orgin < branch name >   # git push origin saurabh

$ git push -f origin main        # to push force-fully 


```

# Optional 

#### create branches 

```bash 

$ git checkout -b <branch name >     # git checkout -b saurabh

```

#### jump from one to another branch

```bash 
$ git checkout <branch name >         # git checkout main 

```



##### to see all commits 


```bash 
$ git log 
```





