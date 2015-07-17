# test
<<<<<<< HEAD
test
test
=======
testing branching and git use for members

##Tasks:
- make your own branch
- make a text file
- add your file and commit
- push your file to your branch
- update your branch from master
- make a pull request to master

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
	% git commit -m "<your message for a commit>"

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
>>>>>>> 67a809efcb8ac12881df22f26623a24e391f9af6
