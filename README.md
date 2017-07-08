
## Terminal commands

To change folder use:  cd folder-name
To list folders use: ls



## Example of how to create a git repository in an existing folder. 

For this example I will be creating a git repository inside a folder called ‘testgit’ which is located the following directory:  /Users/ketilroe/workspace

Open the terminal window and navigate to the testgit folder:

*cd workspace/testgit*

Create a new repository within this folder:

*git init*

Add any files which is in the folder to the git repository

*git add -A*

Commit the the changes/new files. This command commits the tracked changes an prepares them to be pushed to a remote repository.

*git commit -am “Comment of choice”*


You know need to create a new project on Github. On GitHub press ‘Start a project’. Choose a repository name, preferably the same as your folder name (but not necessary). Make sure to leave the box for ‘Initiate this repository with a README’ unticked.  Press create repository. You will now be provided with a link that can be used to push your local copy of the repository to Github. A description to create a new repository from the command line (which we have done above), or push an existing repository from the command line is also provided. Since we already have create a repository we will do the latter:

*git remote add origin https://github.com/username/repository-name*

This will add the path to the online repository. To push the files online use:

*git push origin master*

You may be asked to provide your GitHub username and password.


## Normal workflow for existing repository

When you have worked on your project and want to push the changes to GitHub:

1. If you have created or added any new files make sure to add this files to the repository:

*git add filename*

you can also add all new files by:

*git add -A*

2. Commit changes:

*git commit -am “Comment of choice”*


3. Push changes to GitHub:

*git push origin master*
