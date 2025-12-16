# Git Recap For DevOps

## Basic git commands 
```git init``` initialises a new repository in your project directory and contains all metadata  
```git add <fileName>``` Stages a specific file, and ```git add (.)``` Stages all changes in the current directory and subdirectories  
```git status```  Check the current state of your working directory and staging area.  
```git log --online``` Displays commit history in a compact, single-line format  
```git push```  is used to upload your local commits to a remote repository  

```git clone``` Copy the remote repository to your local system 
```git fetch``` Gets Updates new branches & commits from remote, keeps working branch unchanged (Refresh)
```git pull```  is used to update current local branch with the latest changes from the remote repository 

## Git Branching

```git branch branchName``` Create a new branch example ``` git branch test```  
```git swtich/checkout branchName``` switch into branch  example ``` git switch/checkout test```  
```git checkout -b branchName``` create new branch and switch that branch  
```git switch -c branchName``` create new branch and switch that branch  
```git branch``` show all branch in local
```git branch -a /-r``` shows all branch in local and remote repository

