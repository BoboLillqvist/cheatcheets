## GIT Cheatsheet

## Table of contents
* Configuring
	* User info
* Repositories
* Make changes
* Review history
* Synchronize changes

## Configuring
### User info
* Change **username** and **e-mail:**
	
	```git
	$ git config --global user.name "[name]"
	$ git config --global user.email "[email address]"
## Repositories
* Create new repository and push to remote

	```git
	$ git init
	$ git add -A
	$ git commit -m "first commit"
	$ git add remote [url]
	$ git push -u origin master
	
## Branches 
### Create a branch from a branch

```git
$ git checkout -b myfeature develop
$ git commit -am "Your message"
$ git checkout develop
$ git merge --no-ff myfeature
