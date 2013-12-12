# This is my README

Some useful Git commands

Initial Setup
```
git config --list				-		lists all current config settings
git config user.name			-		list the current config setting for username
git config --global user.name "Daniel Ayewah"	-		sets the user name
```

Working with Git
```
git init				 		- 		creates a new repo
git add ReadMe.md				- 		adds readme file to files staged for next commit
git commit -m "message"			-		perform a commit with a message
git status						-		shows the current status of files

After a file is modified it is necessary to run git add again in order to stage it for the next commit.

git commit adds the version of the file that existed when you sent the command git add i.e. the staged version. 

If the file is modified after git add you have to run git add again to stage the latest version of the file.

git diff 						- 		compares working dir to staged area.
git diff --staged				-		compares staged area to repository

git commit -a -m "message"		-		skips git add for tracked file. Commits all tracked files automatically adding unstaged files first.

git log							- 		view history of commits
git log -p						-		show the log and the corresponding diff
git log -2						-		shows the last 2 log entries
```

Remote Operations
```
git remote						-		lists all remote repositories associated with this repo
git remote -v					-		probably verbose...lists them with their full path
```