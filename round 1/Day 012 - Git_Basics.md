# GIT Basics

## Installation of GIT

[Git_official_Website](https://git-scm.com/downloads)

### Mac
``
$ brew install git 
``

### Linux
``
$ yum -y install git
``

## Find the version of Git
``
$ git --version
``

## Create repository from scratch

1. go to folder of the project (which you want to make repository)
2. run  `` $ git init ``

or

1. run `` $ git init [project-name]``

It will create new local repository with specific name.

## Clone existing git repository

1. go to folder where you want repository folder.
2. run `` $ git clone [url]``

## Make Changes


### Check the status of GIT repository
`` 
$ git status
``

This command list all new or modified files

### Add files to GIT repository
``
$ git add [file-name]
``

OR

If you want to add more than one file

``
$ git add .
``

### Commit file (Permanently Store in GIT)
``
$ git commit -m "Message"
``

Messages are good way to comment on changes.

## Branches

### Create branch
``
$ git branch [new_branch]
``

### Change(Switch) branch
``
$ git checkout [branch_name]
``

### Create branch and switch to new branch
``
$ git checkout -b [new_branch_name]
``

### List all branches
``
$ git branch
``

### Merge branch to current branch
``
$ git merge [branch_name]
``

### Delete specific branch
``
$ git branch -d [branch_name]
``

## Synchronize Changes

### Upload local repository to GitHub
``
$ git push -u origin master
``

### Download repository from GitHub to local machine
``
$ git pull origin master
``
