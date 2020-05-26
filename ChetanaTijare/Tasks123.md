# Tasks

These are questions and answers of **day1**,**day2** and **day3** Tasks:

## Task 1:

1.What is git and Github?

 Git is created by Linus Torvald.git is a distributed version control system. It is designed to track changes to file.Github is a software used for version control. it is useful when more than one person is working on a project.




2.Why Github is so popular and used in most of the projects?

Github is so popular because 
* it makes easy to contribute to your open source projects
* Can be accessed anytime anywhere
* provides secure cloud storage
* documentation.showcase your work
* markdown


3.What are the other platforms similar to Github?
* Gitlab
* Bitbucket
* Beanstalk
* Sourceforge

## Task 2:

1.How git workflow works?
   
workflow is about  controlling the sequence of events.
git workflow consist of 4  fundamental elements.
	
* Workspace
	
* Index(Stage)
	
* Local Repository
	
* Remote Repository
    
The file in the workspace can be in 3 states. It can be committed which means the changes in the file are safely saved to the local repository. It could be modified and it could be staged means the file is the part of the index.

2.what are the diffrent stages of a git project as commit,add?

* clone: creates local copy of repository in the workspace.

* add(-u):add file from workspace to the index.

* commit:All the files which are staged that are listed to the local repository .

* commit -a:add files from workspace to local repository.

* push:it pushes files from local repository to remote repository.

* fetch : get the file from remote repository to local repository.

* merge: gets file from local repository to workspace.

* pull: It takes the file directly from remote repository to workspace.



3 .Is it possible to do a git commit before git add.if you have made any changes ? Explain why?
  
No. It is not possible to do a git commit before git add.


4.why is git diff used?

diff command is used in git to track the difference between the changes made on a file.


5.Can we leave the commit meassage as blank ?
   
git generally requires a non-empty message because providing a meaningful commit message is part of good development practice.But we can use  git commit -a –allow-empty-message -m ' ' command for passing blank message.

## Task 3:

a)What is meant by the term fork and clone??

=>fork is a copy of original repository. By using fork we can get exact copy of original repository and we can update the files without disturbing original repository.
Clone is a command which is used to get copy of remote repository to local repository.

b)what are branches in github?

=>Branches are use for development purpose without affecting other branches it is a 
Movable pointer to one of the commits.

c)What is PR?

=>PR is a pull request.
By using PR  we can request
 someone that we want to contribute to their open source project.

d)Can we delete the master branch if not why?

=>Yes

e)how can we delete a branch?

=>we can delete a branch by using command git branch -d branchname.



_Regards_

_Chetana Tijare_

