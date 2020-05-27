# **Day 1 Task**


##											  Q1. What is git and gitHub?

>Git :	Git is a type of version control system that makes it easier to track changes to files or in the source code.
	It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.
	It is a program installed in a system.
	Its current maintainer since 2005 is Junio Hamano.
	As with most other distributed version-control systems, and unlike most client–server systems, every Git directory on every computer is a
	full-fledged repository with complete history and full version-tracking abilities, independent of network access or a central server.

>GitHub : It provides hosting for software development version control using Git.
	It allows us to create remote repository on website and provides a platform to bring teams together.
	GitHub accounts are commonly used to host open source projects.

##									   Q2. Why GitHub is so popular and used in most of the projects?
>	 1. It supports all programing languages.
	2. Easily accessible
	3. Provides secure cloud storage
	4. Teams can work together easily

##									       Q3. What are the other platforms similar to GitHub?
>		1. SourceForge
       2. Launchpad
	   3. GitBucket
	   4. Gitlab

______________________

#												   **Day 2 Task**


##											  Q1. How git workflow works?

#### Git workflow has 4 fundamental stages:
>1.   Workspace: Working Directory
2.  Index (Stage): It is used as a staging area between working directory and your repository
3. Local Repository is the one on which we will make local changes, generally Local Repository is on our computer.
4.  Remote Repository is the one of the server.

##									Q2. What're the different stages of a git project as commit, add?
#### Git project have 3 different stages
>1.   Modified: Once, the code is written in repository, anyone wants to make some modification can make those changes in their own remote repository.This is called Modification, i.e. making some additions to the original project.
2.  Staged: So, after making changes to the project without hampering the original version, but how do we apply those changes to our remote repository?
So, we use the commands in the Git command line — git add. So, this command tracks the new changes and pushes it to the staging area
where all the new files are finally ready to be joined to the remote repository.
3. Commit: This is the final stage, as this stage finally applies the new changes to the remote repository.
Commit is a set of new files that are being added to a project as part of the modification .

##								    Q3. Is it possible to do a git commit before git add. If you have made any changes? Explain why?

>	No, it is not possible to do git commit before git add. As per git workflow the file must be added to the index or staging area and then it must committed.
Because when commit applies this simply means that you have successfully applied a certain modification to the code.

##											Q4. Why is git diff used?

> git		diff

command is used in git to track the difference between the changes made on a file.

##									     Q5. Can we leave the commit message as blank?

#### Yes we can leave the commit message as blank. It can be done by using the command :
>git commit -a --allow-empty-message -m ""

_____________________

#		**Day 3 Task**

## Q1. What is meant by the term fork and clone?
>	Fork of repository means  we create a copy of the original repository (upstream repository) but the repository remains on our GitHub account. Whereas, when we clone a repository, the repository is copied on to our local machine with the help of Git. It can be clones on any folder we want.
##	Q2. What are branches in Github?
>	A branch is an individual project pr files inside a repository. The default branch is the Master branch. Once we have made changes in the file we can merge that branch to the master branch. All the branches are independent to each other. We can made new branches in master branch .
##	Q3. What is PR?
>	PR stands for Pull Request. User issues a pull request if he has forked and cloned someone’s else code and modified it and want to publish that code on the author’s repository. Then a pull request is issued.  The one who has created the repository can review and then approve the request to incorporate the changes that has been created.
##	Q4. Can we delete the master branch if not Why?
>	No. we cant delete Master branch as soon as we use command " git init", Master branch gets activated by default.      git push origin :masterThis will push nothing (the part before the colon) to your origin server and overwrite master. In other words, it should delete the master branch remotely.


##	Q5. How can we delete a branch? 
#### To delete the local branch use one of the following:
>	 git branch -d branch_name

#### To delete the remote branch use one of the following:
>	 git push <remote_name> --delete <branch_name>

______________
## Links :

[**My Repo**](https://github.com/prathamesh613/)

[*Clone*](https://github.com/prathamesh613/gitseries)

[*Pull Request 1*](https://github.com/deepak2431/gitseries/pull/47)

[*Pull Request 2*](https://github.com/deepak2431/gitseries/pull/48)
