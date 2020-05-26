# Question and Answers

## TASK 1

- What are git and GitHub?

   Git is Distributed Version Control System.This means that every user will have their own copy of program at their local repository along with having it on the remote repository.It is free and open source.

   Github is a web service which implements the remote repository.



- Why GitHub is so popular and used in most of the projects?

   Github uses Trunk Based Development.This implies that the user can work on different versions/branches and merge them together.
As it is Distributed Version control System so if the remote server fails then the users data would not be lost as it is already available in the local repository.




- What are the other platforms similar to GitHub?
   Bitbucket 
SourceForge





## TASK 2

- a.How git workflow works?

- b.What're the different stages of a git project as commit, add?


- Git workflow consists of

---Workspace(Working Directory

---Index(Stage)

---Local Repository(Head)

---Remote Repository 

    clone command creates a local copy of the repository in the workspace/working directory.



    add command adds the file from workspace to the Index.



    commit command saves the file in the local repository 



    Note: commit -a command does the both work of add and commit command.



    push command saves the file from local to remote repository.



    Now the reverse process goes like this:



    fetch command gets the file from remote to local repository.



    merge command gets your file from local tow workspace.



    pull command takes the file directly from remote repository to workspace.








- c. Is it possible to do a git commit before git add . if you have made any changes? Explain why? 


    No, when I did,then it asked to first add the file.




- d. Why is git diff used?

    It is used to differentiate between the working depository file and the files which are staged for commit.




- e. Can we leave the commit message as blank?

    No......but we can add this command to do so
git commit -a –allow-empty-message -m ' '




Github repository link

https://github.com/absaditi6/Codewayy





## Task 3

- a. What is meant by the term fork and clone?

     Fork means creating a personal copy of someone else's project and modifying it.
     Someone else's project can be used as the beginning of someone else's project.
     Clone is used to create  a local copy of the remote repository.




- b. What are branches in Github?

     A branch is an independent line of development.
     It means all the branches are independent of each other.

     Branches are like movable pòinters to the commits.

     The default branch is known as master branch.


- c. What is PR?

     Pull Request allows others to know about the changes one has pushed in the github repository.
- 


d. Can we delete the master branch if not Why?

     Yes

. 
- e. How can we delete a branch?
     
git branch -d name of the branch



       
https://github.com/absaditi6/gitseries/pull/1
       https://github.com/absaditi6/gitseries/pull/2
…