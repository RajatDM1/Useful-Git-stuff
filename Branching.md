##Create a branch

change to the repository directory on your computer(if you are not already there):

    cd <repository name>

Now create a branch using the ``git checkout`` command:

	git checkout -b <new_branch_name>

To check which branch you are on:

	git branch

To merge this new branch to the origin 

	git push origin <new_branch_name>

To check the which url belongs to each remote 

	git remote -v

In the push command, you can use remotes or you can simply use a url directory. Eg:

	git push git@github.com:git/git.git master