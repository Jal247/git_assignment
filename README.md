# Git Assignment - <Jal247>


a. What is an issue?
Github issue is an item that is created in the current repo. The intend of issue is to higlight any barrier/hotfix, or bugfix,or checklist, or adding new feature/important information related to project in that repo. which is useful to track task on project work and can be close once related issue is resolved.

b. What is a pull request?
A pull request is a praposal or request to merge changes made on project/feature by various member of team. by pull request it gives the latest version of the project/file/feature to the current working machine. It is always a good step to perform pull request to have a latest version of file.   


c. Describe the steps to open a pull request?

pull request by gitbash:
1. login to gitbash, 
2. Clone the github to local machine(only need to do first time)
2. Go to the repo and desired brach
3. write command $ git pull
4. press enter 
5. once process complited, open file by command $ cat filename

pull request on github
1. login to github
2. go to the desired repo and branch
3. click on 'Pull request' tab
4. click on 'New pull request' button
5. Open a pull request , confirm the changes across two branches and forks
6. write Pull request meaningful description 
7. and confirm open pull request



d. Describe the steps to add a collaborator to a repository (share write permissions)

 1. on a Github, go to the repository where you want to add collaborator.
 2. Go to the Settings
 3.go to the Manage access
 4. click on the Add people button
 5. 'Add a collaborator to git-module' window will pop up.
 6. enter the person's username or full name or email id.
 7. click on select a collaborator above.
collaborator will be added to a repository, enables to make chages/write permissions and push them to the repo without constant permission.


e. What is the difference between git and GitHub?

1. git is a Version Control System, which allows user to operate locally, make chages on locat machine and when needed merge all chages to remote server/machine.
git assures integrity of data/file. git can allow user to track version of file as well as modify file in various way such as VS Code, Nano. 
In general it is a one system for all combination of work performed by team at the same time or different time, And stay update with the latest changes or notification related to project.

2. GitHub is a hub developed by professional developers. Where everyone can 
 - look and mange at the project feature/featrues at the same time
 - create,store,share and learn the code
 - anyone can collobrate for the learning, knowledge sharing purpose 


f. What does git diff do?
 git diff command show the details of the changes made. 
 It compares what is in current directory and what is in our staging area.
 We can compare difference between previous file and current file. It can compare repositories too.

g. What is the main branch?
 The main branch is the default/initial branch that is created by git when new or clone of the repository created.It is the default branch in the repo for new pull requests and code commits. 


h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

On main branch after initial commit, we can check status of commit by $git status and then we can directly push changes by command $ git push.
IF new branch is created on terminal then after commit, we have to save new branch on github(origin) before pushing.
This can be done by the command $git push --set-upstream origin assignment      
