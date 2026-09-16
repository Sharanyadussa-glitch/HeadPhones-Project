# HeadPhones-Project

# Git

## Clone a repository
- git clone https://xxxxx (the URL to the repo you are cloning, from Github)

### Git commands that we have looked at
- git pull
	- Pull down all of the changes available in the main remote branch (on Github)
- git branch
	- You can see all of the avaible branches in your repo
- git checkout -b other-branch (name of your own branch)
	- This will create a new local branch that you go into
- git branch
	- Now you can see that you have switched from main branch to your own
- Add some changes to a file
- git add . or your seperate files
	- Adds your changed files
- git commit -m "Commit message"
- git push -u origin other-branch
	- This will push up your code and at the same time create the branch in your remote repo (on Github)
- git checkout main
	- This takes you into the main branch again

### Workflow on a daily basis
- git branch to confirm which branch you're in. You should be in the main branch.
	- If you are not in the main branch use git checkout main to switch to it
- git pull
	- pulls down all of the code from the remote repository (github repo)
- git checkout other-branch (the name of your own branch)
	- Now you go in to your own branch
- git pull
	- This takes the changes from the main branch branch in to your own branch
- git merge origin/main
	- This will merge all of the new changes from the main into your own branch
