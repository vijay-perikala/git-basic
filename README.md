# GIT BASICS - COMMAND LINE  <img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="28px" alt="hi">


## [![git config](https://img.shields.io/badge/-git_config-7EBDC2?style=for-the-badge&labelColor=black&logo=git&logoColor=7EBDC2)](#)
`syntax`:`git config –global user.name “[name]”`

            git config –global user.name “vijay”

`syntax`:`git config –global user.email “[email address]”`

`example`:`git config –global user.email “vijay@perikala.com.my”`


## [![git init](https://img.shields.io/badge/-git_init-2B7A78?style=for-the-badge&labelColor=black&logo=git&logoColor=2B7A78)](#)

`syntax`:`git init "[repository name]"`

            git init “git-basic”

## [![git clone](https://img.shields.io/badge/-git_clone-4f0c6e?style=for-the-badge&labelColor=black&logo=git&logoColor=4f0c6e)](#)

`syntax`:`git clone "[url]"`
       
            git clone "https://github.com/vijay-perikala/git-basic.git"

## [![git ADD](https://img.shields.io/badge/-git_ADD-24305E?style=for-the-badge&labelColor=black&logo=git&logoColor=24305E)](#)

###### Note:  Adds only certain file(s)
`syntax`:`git add [file]`

            git add "sampletextfile.txt"
---
###### Note:  Stages everything, but not files that begin with a dot & does not remove files that have been deleted from the disk  
`syntax`:`git add *`

            git add *
---
###### Note:  Adds everything, so that everything in your folder on disk is represented in the staging area  

`syntax`:`git add -A (--all)`

            git add -A

---
###### Note: Stages everything, but does not remove files that have been deleted from the disk  

`syntax`:`git add . `

            git add . 

---
###### Note: (--update) Stages only Modified Files, removes files that have been deleted from disk, does not add new

`syntax`:`git add -u`

            git add -u 

---



## [![git_commit](https://img.shields.io/badge/-git_commit-F3DFA2?style=for-the-badge&labelColor=black&logo=git&logoColor=F3DFA2)](#)

`syntax`:`git commit -m “[ Type in the commit message]”`

            git commit -m “Initial commit”

`syntax`:`git commit -a`

            git commit -a


## [![git_diff](https://img.shields.io/badge/-git_diff-EFE6DD?style=for-the-badge&labelColor=black&logo=git&logoColor=EFE6DD)](#)

`syntax`:`git diff`

            git diff

`syntax`:`git diff –staged`

            git diff –staged

`syntax`:`git diff [first branch] [second branch]`

            git diff vijay-master vijay-develop


## [![git_reset](https://img.shields.io/badge/-git_reset-BB4430?style=for-the-badge&labelColor=black&logo=git&logoColor=BB4430)](#)

`syntax`:`git reset [file]`

            git reset "sampletextfile.txt"

`syntax`:`git reset [commit]`

            git reset 23434444

`syntax`:`git reset –hard [commit]`

            git reset –hard 5454444

## [![git_status](https://img.shields.io/badge/-git_status-70587C?style=for-the-badge&labelColor=black&logo=git&logoColor=70587C)](#)
`syntax`:`git status`

            git status

## [![git_remove](https://img.shields.io/badge/-git_remove-502F4C?style=for-the-badge&labelColor=black&logo=git&logoColor=502F4C)](#)
`syntax`:`git rm`

            git rm "sampletest.txt"

## [![git_log](https://img.shields.io/badge/-git_log-F9F4F5?style=for-the-badge&labelColor=black&logo=git&logoColor=F9F4F5)](#)
`syntax`:`git log`

            git log

            git log –follow "sampletest.txt"

## [![git_show](https://img.shields.io/badge/-git_show-9CF8A1?style=for-the-badge&labelColor=black&logo=git&logoColor=9CF8A1)](#)
`syntax`:`git show [commit]`

            git show 324343

## [![git_tag](https://img.shields.io/badge/-git_tag-51BBFE?style=for-the-badge&labelColor=black&logo=git&logoColor=51BBFE)](#)
`syntax`:`git tag [commitID]`

            git tag 324343

## [![git_branch](https://img.shields.io/badge/-git_branch-F7FE72?style=for-the-badge&labelColor=black&logo=git&logoColor=F7FE72)](#)
`syntax`:`git branch`

            git branch 
`syntax`:`git branch`

            git branch 
## [![git_branch](https://img.shields.io/badge/-git_branch-F7FE72?style=for-the-badge&labelColor=black&logo=git&logoColor=F7FE72)](#)
git branch
Usage: git branch
Usage: git branch [branch name]
Usage: git branch -d [branch name]

git checkout
Usage: git checkout [branch name]
Usage: git checkout -b [branch name]

git merge
Usage: git merge [branch name]

git remote
Usage: git remote add [variable name] [Remote Server Link]

git push
Usage: git push [variable name] master
Usage: git push [variable name] [branch]
Usage: git push –all [variable name]
Usage: git push [variable name] :[branch name]


git pull
Usage:  git pull [Repository Link]

git stash
Usage: git stash save
Usage: git stash pop
Usage: git stash list
Usage: git stash drop