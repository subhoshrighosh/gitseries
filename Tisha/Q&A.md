# Questions and Answers
## Task1:
Hello , My name is Tisha Jain. I am currently pursuing B.Tech in Computer Science
1.What is git and gitHub?
Git-Git is installed and maintained on your local system (rather than in the cloud) and gives you a self-contained record of your ongoing programming versions. It can be used completely exclusive of any cloud-hosting service — you don’t even need internet access, except to download it. Git is responsive, easy to use, and inexpensive.
GitHub-GitHub is designed as a Git repository hosting service. GitHub is a for-profit service (although basic repository-hosting features are available at no cost to those who are willing to create a user profile.
2.Why gitHub is so popular in most of the project?
It provides cloud storage for source code, supports all popular programming languages, and streamlines the iteration process.
3.What are the other platforms similar to github?
Bitbucket
GitLab
Phabricator
Sourceforge

## Task2:
git workflow works?
 Ans The idea is simple: 
•There is one central repository. 
•Each developer clones the repo, works locally on the code, makes a commit with changes, and push it to the central repository for other developers to pull and use in their work.
2.What are the different stages of git project?
 Ans 
• Modified:* 
So, under Git we can create a repository, a repository is basically a kind of a directory that contains all the files related to your code. So, in the repository we can write code, and maintain it. Once, the code is written, anyone willing to make some modification can make those changes in their own remote repository. A remote repository is a local copy (one that you create on your local machine) of the original project that is being maintained via Git. So, basically you can make changes to your copy of the project without hampering the original code. This is called Modification, i.e. making some additions to the original project.
• Staged: 
So, we saw that we can make changes to the project.We use the commands in the Git command line — git add. So, this command tracks the new changes and pushes it to the staging area. So, staging area is place prior to the actual implementation of changes, i.e. this area contains all the added files that contain new code, which are ready to be joined to the remote repository. So, all the new files are first pushed to the staging area.
• Commit: 
This is the final stage, as this stage finally applies the new changes to the remote repository. So, a commit is a set of new files that are being added to a project as part of the modification. Each commit represents the changes made to project in the past, with the details about the time at which commit was made and the author of the code. So, finally when you make a commit, and it gets committed, then this simply means that you have successfully applied a certain modification to the code.
3.Is it possible to do a git commit before git add?If No,explain why?
 Ans No, it is not possible as git add command add changes in the working directory and then the changes are saved using commit command.
3.Why is git diff used?
 Ans Difference command is used to track the differences or changes made on a file in a working directory.
4. Can we leave the commit messages as blank?
 Ans Yes,we can do that by using the command 
 git commit -a --allow-empty-message -m "" 
My github repo link is
https://github.com/Tisha-03/Digit-Recognition/blob/master/README.md

## Task3:
1. What is meant by fork and clone?
 Ans. Fork means you just create a copy of the main repository of a project source code to your own GitHub profile. 
So,When you fork a repository, you create a copy of the original repository (upstream repository) but the repository remains on your GitHub account. 
 Clone 
When you create a new repository on GitHub, it exists as a remote location where your project is stored. You can clone your repository to create a local copy on your computer so that you can sync between both the local and remote locations of the project.
2.What are branches in GitHub?
 Ans. 
A branch is a lightweight movable pointer to one of these commits. The default branch name in Git is master . As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically. The git branch command lets you create, list, rename, and delete branches.
3.What is PR?
PR refers to Pull Request.
When you make local code changes and then submit those changes to a remote project maintainer for review before those changes are implemented, or merged.
This is called a pull request; you are requesting that someone reviews and approves your changes before they become final.
4.Can we delete the master branch?
 Ans. Yes,we can delete the master branch by changing the deafault branch from master.
5.How can we delete a branch?
 Ans. we can delete a branch by the following command:
 git branch -d 
The -d option will delete the branch only if it has already been pushed and merged with the remote branch. Use -D instead if you want to force the branch to be deleted, even if it hasn't been pushed or merged yet.
PR links:
https://github.com/deepak2431/gitseries/pull/15
https://github.com/deepak2431/gitseries/pull/19
