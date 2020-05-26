# "QUESTION  & ANSWERS"
TASK 1

Hi everyone!
I am Yukta Gaba, pursuing B.Tech in Computer Science from DIT University, Dehradun.

1.What are git and GitHub?
Git is created by LINUS  TORVALDS. It is an open-source, free and distributed version control system. Git has trunk based development in it which involves branches in the repository in which we can create new branch even while working with the current branch and also we can merge the new branch with the master branch if required at any point.
GitHub is a website which in which we can upload projects that’ve version control on them. GitHub is a file or code sharing service to collaborate with different people. 

2.Why GitHub is so popular and used in most of the projects?
GitHub is popular as:
•	It has an extremely large community of developers
•	Separate public and private repositories
•	Shared Repositories which can be accessed by millions of users and make contributions to existing files or codes
•	Easy Version Control
•	Can be accessed anytime and anywhere

3. What are the other platforms similar to GitHub?
GitLab
GitBucket
Source Forge
AWS Code Commit



TASK 2

1.How git workflow works?
 Ans1. There is one local repository and the developer that wants to make changes clones the repository and make changes using the commit command and further pushes it to the remote repository from where developers can pull and use in their work.

2.What are the different stages of git project?
 Ans2. 
• Modified:
A repository is created using Git through the files that are stored in a particular folder. Anyone can make changes to a repository that is public by cloning them inside their system and modify as their requirement and then uploading it onto GitHub so that the file can be used for Staging.
• Staged: 
Git add command is used to add a file from the workspace or the working directory to the Index or the staging stage. After that the file is staged i.e., it is marked to commit but is not yet committed.
• Commit: 
When we used the Git commit command, all the files that were staged in the Index are released here and the changes are committed to the local repository. Each commit command represents the changes made to project in the past, with the details about the time at which commit was made and the author of the code. So, finally when you make a commit, and it gets committed, then this simply means that you have successfully applied a certain modification to the code.

3.Is it possible to do a git commit before git add?If No,explain why?
 Ans3. No, it is not possible as git add command adds the files from the working directory to the staging area and then the changes are saved using commit command in the local repository.

4. Why is git diff used?
 Ans4. Git diff command is used to track the differences or changes made on a file in a local or a working directory from the Index/staging state.

5. Can we leave the commit messages as blank?
 Ans5. Yes,that can be done using the following command 
 git commit -a --allow-empty-message -m "" 

My GitHub repository link is:
https://github.com/Yukta1999/git_learn_series

Thank you
YUKTA GABA (DIT University)




TASK 3

PULL URL:
https://github.com/deepak2431/gitseries/pull/13
https://github.com/deepak2431/gitseries/pull/14

a.What is meant by the term fork and clone?
Fork means creating a personal copy from someone else’s project and that copy can also be used as a person’s initial point of creating a project. Also, it can be modified by the developers around the world and they can publish their own changes to it.
Clone is used to create the local copy of someone’s git repository from the GitHub in our system  from the remote repository.

b. What are branches in Github?
Branches are an individual projects within a git repository. Branches are like movable pointers to the commits. All the branches are independent of each other. The default branch is the Master branch. Once we have made changes to a project we can merge that particular branch to the master branch. It is used mainly to reduce redundancy in the project.

c. What is PR?
PR stands for Pull Request. User issues a pull request if he has forked and cloned someone’s else code and modified it and want to publish that code on the author’s repository. Then a pull request is issued.  The one who has created the repository can review and then approve the request to incorporate the changes that has been created.

d. Can we delete the master branch if not Why?
Yes, we can delete the master branch but then we’ll have to create a new branch and set it as our default branch

e. How can we delete a branch? 
Using Git Bash we can do as follows:
To delete locally: 
git branch -d <branch>
To delete remotely:
git push <remote> --delete <branch>


Regards
YUKTA GABA



 
