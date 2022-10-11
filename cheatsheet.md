create a repository   >>mkdir  repository name
go into the repository >>cd repository name 
initialize the repository >> get init
make some changes
to add any file to the repository>>git add filename 
to be able to see what are you  >> git status

to commit the changes >>  git commit -m “ argument”
create repo on github
to connect git and github >> get remote add origin <url>
to push the change to the repository at github >> git push origin master


test changing 
  
Usfull links: 
  

https://education.github.com/git-cheat-sheet-education.pdf
https://wac-cdn.atlassian.com/dam/jcr:e7e22f25-bba2-4ef1-a197-53f46b6df4a5/SWTM-2088_Atlassian-Git-Cheatsheet.pdf?cdnVersion=315

Commands: 
  Associate your name and email with your work:
git config --global user.name "Your Name Comes Here"
git config --global user.email you@yourdomain.example.com

Initialize repo: (created a local repo within your project contained in the hidden directory .git. This is where all of your change history is located on your local workstation.)
Git init 

Checking repo status:
Git status

Create file called first.txt:
Echo "Our best thoughts came from others." >> first.txt

Add changes to stage your work:
Git add first.txt

Commit changes with description message:
Git commit -m "Add inspirational quote" 

Reviewing the most recent commit history:
Git log

You can review and compare changes among commits. You can do that with the command git diff <commit> <commit>. Use the git log command to find two commits to compare.
git diff  7be53cc  d553bb

Create new branch:
Git branch <name of the new branch> 

Check branches:
Git branch

Navigate between branches:
Git checkout <branch name> 

Creating new branch and switch to it:
Git checkout -b <new branch name>

To merge branch with main branch: 
	1. Switch to the main branch using git checkout main command
	2. Git merge <name of the branch you want to merge> 
	3. In case of conflicts you have to fix them manually. 
	
Once a branch mas been merged into main, you can delete your working branch with the following command:
 git branch -d <branch name> 

Stash your work:
Git stash

This command takes the changes you have stashed, adds them back to your file, and deletes the stash.
Git stash pop 

Now you can commit it![image](https://user-images.githubusercontent.com/7130396/194982620-f1e7e245-fd24-4003-b15b-8bf6a3104922.png)
