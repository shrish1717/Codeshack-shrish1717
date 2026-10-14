# Git Command Notes
This document contains useful Git commands and examples that I am learning during CodeShack Week 1 Task.

- ## Git Configraturation and Repository Setup


*1. Command:* `git --version`
### Description: 
It Check the installed Git version of git.
***Example:***
`git  --version`
git version 2.56.0.windows.1


*2. Command:* `git config --global user.name "User's Name"`
and   `git config --global user.email "User's Email"` 
### Description:
They sets user name and email in Git respectively so that Git can identify who made a commit.
***Example:***
`git config --global user.name "Srishti Sonam"`
Here, global means it will apply this setting to all my local Git repositories.


*3. Command:* `git config --global --list`
### Description:
It shows only the Git settings saved globally on a computer. These settings apply to all local repositories by default in that local system.
***Example:***
`git config --global --list`
user.name=Srishti Sonam
user.email=shri.work177@gmail.com


*4. Command:* `git config --local --list`
### Description: 
It displays the Git configuration settings for the current repository only.


*5. Command:* `git config --local user.name "User's Name`
and `git config --local user.email "User's Email`
### Description:
They sets the username  and email for the current Git repository only.


*6. Command:* `git init`
### Description:
It initializes a new Git repository in the current folder and allows Git to track changes in specific files.
***Example:***
`git init`
mkdir Codeshak-shrish1717
cd Codeshack-shrish17
git init

Initialized empty Git repository in C:/Users/sonam/Codeshack-shrish1717/.git/

Here, I am making a directioy as Codeshak-shrish1717 using mkdir and going into that folder using cd command.
 After that I am initializing it using git command


*7. Command:* `git clone <repository-url>`
### Description:
It downloads a repository from GitHub to a particular computer and creates a local copy of it.
***Example:***
`git clone https://github.com/username/Student-Notes.git`
Cloning into 'Student-Notes'...
remote: Enumerating objects: 10, done.
Receiving objects: 100% (10/10), done.



- ## Checking Status and Differences
*8. Command:* `git status`
### Description:
It shows the current state of working directory, including modified, staged, and untracked files.
***Example:***
On branch main
Untracked files:
  notes.txt

nothing added to commit but untracked files present


*9. Command:* `git diff`
### Description:
It shows the changes made to files that have not been staged yet.


*10. Command:* `git show`
### Description:
It displays details of a commit, including its author, date, commit message, and changes.


***Example:*** Dummy output
commit a1b2c3d
Author: Sonam <sonam@example.com>
Date:   Wed Oct 14 10:00:00 2026

    Update notes

diff --git a/notes.txt b/notes.txt
- Hello World
+ Hello Git

- ## Staging, Committing and Viewing History

*11. Command:* `git add <file>`
### Description:
It stage a specific file, means it's ready to be committed.

***Example:***

*12. Command:* `git add .`
### Description:
It stage  all the changes, made in a specific forlder.

*13. Command:* `git commit -m "message`
### Description:
It saves the staged changes as a commit in Git with a short message describing what was changed.

*14. Command:* `git log`
### Description:
It displays the history of commits in the repository, including the commit ID, author, date, and commit message.
***Example:***
Author: Srishti Sonam <shri.work177@gmail.com>
Date:   Wed Oct 14 01:12:21 2026 +0530

    Add README.md File


*15. Command:* `git push`
### Description:
It upload the local commits to a remote repository like GitHub repo.
***Example:***   
`git push origin main`
It reflect the specific changes made in the local folder in main branch to remote resposit


*16. Command:* `git pull`
### Description:
It download the latest changes from the remote repository and merge them into our current branch.
 

 



















