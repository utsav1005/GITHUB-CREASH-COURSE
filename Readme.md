## Git Hidden Folder

There is a hidden folder called `.git` which tells you that our project 
is  a git repo to see hidden folder 👇👇👇. 
```sh
ls -la 
``` 
If we wanted to create a git repo in a new project we create the folder 
and the initialize that repo using `git init`
```
git init
touch Readme.md
code Readme.md
git status
git add .
```

## Cloning
 we can clone three ways : HTTPS , SSH , Github CLI

 ```sh
mkdir /workspaces/tmp
cd /workspaces/tmp
 ```
 

## HTTPS

```sh
git clone https://github.com/utsav1005/GITHUB-CREASH-COURSE.git

```
## Commits

when we want to commit code we can write ```git commit ```
```
git commit
```
to write messsage in commit
```
git commit -m "message"
shows commits in inline
```
git log --oneline
```

Set the global editor
```
git config --global core.editor emacs
```

## Branches

## Remotes

## Stashing

## Merging


## Add

when we want to stage changes that will be included in the commit 
we can use the . to add all files

## status

Git Status shows you what files will or will not be commited.
```
git status
```
## Gitconfig file
The gitconfig file is what stores your global configuration for git such
as email , name , editor and more

showing contents of our .gitconfig file
git config --list
```
when you first install Git on a machine you are suppose to set up 
your name and email
```
git config --global.user.name "Joha Doe"
git config --global.user.email "johndoe@exmaple.com
```
## push
When we want to push repo to our remote origin
```
git push orgin 
```

## Reset
Reset allows you to stash changes to unstashed.
this is useful when you to revert all files not to be not commited 
```
git add .
git reset
```