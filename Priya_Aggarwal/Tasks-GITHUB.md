## Task 1
Hey..!
Myself Priya Aggarwal, I am currently pursuing BTech in computer science from DIT University dehradun.

1. What are Git and GitHub ? Why Github is so popular in most of the projects? 
Git is a popular control system which is installed and it maintains all your local system and gives you a self contained record if your ongoing programming versions. Best part about Git is that you dont need internet connection to access it and its is free of cost and easy to use. 
GitHub is designed as a Gut repository hosting service. Git repository hosting is an online database that allows you to keep track of your work and shares your Git projects outside the local server. It is popular for open source projects. If the server is failed then the data is not lost since it is saved in your local repository.


2. what are the other platforms similar to Github?
a. GitLab
b. Google cloud source repositories 
c. AWS Code commit 
d. Apache Allura 
--------------------------------------------------------------------


## Task 2

Q1 How git workflow works?
Q2 What are the different stages of a git 
the project as commit, add?
Ans.
1. Working directory - Workspace.
2. Index ie stage
3. Local Repository ie Head
4. Remote Repository
----------------------------------
There is one central repository. 
Each developer clones the repo,
works locally on the code,
Modifies and makes the changes as required
Commit the changes using command commit -a with changes
and push it to the central repository 
for other developers to pull and use in their work.


Q3 Is it possible to do a git commit before git add .
If you have made any changes? Explain why?
Ans. No, because according to the process
first, we have to add the file and then commit changes to it
After making the changes we will add them using "git add ."
and then we can commit it using (commit -a).

Q4 Why is git diff used?
Ans. git diff is used to track the difference between the changes made on a file. This command shows all the
changes which are done. Diff command takes two inputs and 
reflects the differences between them. It is not necessary
that these inputs are files only. 
It can be branches, working trees, commits and more. 

Q5 Can we leave the commit message as blank?
Ans. git commit -a --allow-empty-message -m ""
It is a valid request,commit can have no message at all.
 
Github repository link
https://github.com/priya8936/java-JFrames-Listeners

Regards
Priya Aggarwal
------------------------------------------------------------------------
## Task 3
Day 3 Task 
Q1 What do you mean by fork and clone ?
Ans 1. Fork - We create a copy of the main repository of a project source code to our own github profile. In this we can do any changes without affecting the main source of the project. Fork repository makes a connection between our fork and the original repository and we can go back to the original project using pull request. 
We do clone to make our own repository on our local computer. We cannot pull the changes from the original repository when clonning. 

<<<<<<< HEAD
Task 3
=======
Q2. What are branches in Github ? 
Ans 2. When we create a repository, then the main linear list of commits are on master branch. We can makes changes in master as well as in a new branch. All the branches are independent of each other. After editing we can commit the changes in the branch directly or create a new branch. 

Q3. What is PR ? 
PR stands for pull request. 
It lets others know about the changes we have pushed to a branch in a repository of github. Once the pull request is open we can discuss and review it before the changes are merged into the main brach. 

Q4. Can we delete the mastar branch if not why ? 
Ans 4. Yes we can delete the master branch. 

Q5 How can we delete the master branch ?
Ans 5. First delete the master in your local clone. We can make a new branch first and delete the master. 
We cannot delete the master branch directly from github instead first we will make github look for our new branch and then delete the master branch. To do so we will push the new branch then set the new branch to github default branch then go to main github page for your forked repository and click on admin button and you are done its set as default. 

1. Forked - https://github.com/deepak2431/gitseries/tree/master/Priya_Aggarwal
2 PR Branch- https://github.com/priya8936/gitseries/tree/master

Regards 
Priya Aggarwal
