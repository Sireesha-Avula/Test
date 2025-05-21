# 3rd Project

## Create a Folder
```
mkdir BranchingStrategy
cd BranchingStrategy/
```

## Main branch commit
```
    git status
    git init
    touch 1.txt
    git add .
    git commit -m "sample file"
    git config user.name pvishnutech
    git config user.email pvishnutech@gmail.com
    git commit -m "1st commit sample file"
    git status
```
## Release branch creation
```
    git branch Release
    git branch
    git checkout Release
    git branch
```
## Develop branch  creation
```
    git branch develop
    git checkout develop
```
## Feature branchs creation
```
    git checkout -b feature1
    touch feature1.txt
    git add .
    git commit -m "feature1 code"
    git checkout develop
    git checkout -b feature2
    touch feature2.txt
    git add .
    git commit -m "feature2 file"
    git checkout develop
    git checkout -b feature3
    touch feature3.txt
    git add .
    git commit -m "feature3 file"
    git checkout develop
    git checkout feature1
    git checkout feature2
    git checkout feature3
    git checkout develop
```
## Merge of feature branches to develop branch
```
    git merge feature1
    git merge feature2
    git merge feature3
```
## Merge of develop branches to release branch
```
    git checkout Release
    git merge develop
    git checkout main
    git merge Release
```
