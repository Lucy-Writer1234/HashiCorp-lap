# HashiCorp-lap
writing assignment
Using the Git commands push, pull, and fetch with your repository

An open source distributed version control system, use Git to manage your mainline and branches for your code. When first starting with Git, you may have difficulty understanding the purpose of the commands as some functionality may seem similar. 

For instance, git pull and git push can be described as equivalent commands, but differences do exist between the two commands:

•	git pull – This command performs a git fetch and immediately follows with the command, git merge. You may prefer to use the command, git pull, but you can also use the command, git fetch, followed by git merge to understand the changes merging into the branch before the merge happens.
•	git push – Reads the current branch and looks for an existing branch in a remote repository. If a remote branch exists, the command reads the changes from the current branch and pushes the changes to the remote branch. Add changes from a remote repository to synchronize the remote branch with the local branch. 

The git push command fails if your remote branch diverges from your local branch without remote branch commits in your local branch. When this occurs, synchronize the local and remote branches with git pull or git fetch, and then the git merge command. 

Using the git fetch command takes your current branch and checks for a tracking branch. If a tracking branch exists, git fetch compares the changes in the remote branch, and pulls the changes into the tracking branch. Your local branch does not change. To add the changes to your local branch, use the command, git merge origin/master, on the master branch and merge the changes into your master branch.
