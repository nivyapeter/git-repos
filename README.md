## Git commands
1) git config 
	  - To set your user name and email in the main configuration file.

2) git init 
	-  To initialise a git repository for a new or existing project.

3) git clone 
	-  To copy a git repository from remote source.

4) git status 
	-   To check the status of files you’ve changed in your working 		directory.

5) git add
	-   adds changes to stage/index in your working directory.

6) git commit 
	-   commits your changes and sets it to new commit object for your 		remote.

7) git push/git pull 
	-   If you have added and committed your changes and you want to push 		them.
	
	if your remote has updated and you want those latest changes.

	--> git pull <:remote:> <:branch:> 
	--> git push <:remote:> <:branch:>

8) git branch 
	 -  Lists out all the branches. 

9) git checkout 

	--> git checkout <:branch:>
	Switch to different branches

	--> git checkout -b <:branch:> 
	create and switch to a new branch.

10) git stash 
	 -  Save changes that you don’t want to commit immediately.

	--> git stash pop ==> for getting back locally save code.

11) git merge 
	 -  Merge two branches you were working on.

12) git reset 
	 -  you know when you commit changes that are not complete, this sets 		your index to the latest commit that you want to work on with.

	--> git reset <:mode:> <:COMMIT:> 

13) git remote 
	 -   To check what remote/source you have or add a new remote.
	--> git remote -v

14) git diff
	  -     to review changes before committing them.

15) git log
	 -  classic git branch timeline view.
	--> git log --oneline 
	
16) git grep 	
	-   Search the working directory for foo():
	--> git grep <:working directory:>