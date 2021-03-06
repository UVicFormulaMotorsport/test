# test
testing branching and git use for members

##Tasks:
- make your own branch
- make a text file
- add your file and commit
- push your file to your branch
- update your branch from master
- make a pull request to master

##Valuable Reads!!!:
####The importance of a good commit (also funny):
- https://github.com/torvalds/linux/pull/17

####How to do a good commit:
- http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html

##Notes:
###Windows:
Please note that, while the Windows version of Git has a Git Shell Extension
which recognizes all commands in the README. Pull request can be done locally 
(ie not on the website) and there are ways to do all pulls / checkouts 
through the GUI.

##How to:

###Make a branch:
#####Make a Local Branch
	% git checkout -b <branch name>

#####Make the branch remote
	% git push origin <branch name>

###Make a Text File:
Using vim or another text editor, create a file of your choice.

###Add File to git and Commit:
#####Add file to Git:
	% git add .    (note, this adds all files in current directory!)

#####Commit files added:
	% git commit --verbose 
- Enter the commit message. Remember! The first line is the commit header and further lines are the body. 
- Make sure to keep it wrapped to 72 characters or less on each line!! (see above "How to do a good commit")

####Push your file to your branch:
	% git push origin <branch name>

###Update your branch from master:
#####switch branch to master:
	% git checkout master

#####update your master copy with latest version:
	% git pull origin master

#####switch back to your branch:
	% git checkout <branch name>

#####merge master into your branch:
	% git merge master

###Now fix any possible conflicts in your files!

###Make a pull request:
- Go onto github and on the right side there is "Pull Requests" under the "test" repository.
- Once under the "Pull Requests" section, make a new pull request (green button).
- Use your branch and make a comment for the pull request.

