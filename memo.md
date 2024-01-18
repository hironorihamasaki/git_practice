Git primarily operates in three different states:

1. Working Directory: This is your current project directory where you're making changes to your files. 
2. Staging Area (Index): This is an intermediate area where commits can be formatted and reviewed before completing the commit.
3. Repository (HEAD): This is where Git stores the data for the committed snapshots of the project (in the .git directory). 


`git status` : check status


`git checkout -- .` : discard all changes in the working directory that have not been added to the staging area or committed yet. It takes the versions of all the files from the staging area (the "index") and copies them to the working directory.

`git reset HEAD .` : unstage all files that may have been added to the stage. 

`git add .` : reflect all local changes to a stage

`git restore --staged <file_name>` : undo `add` with the local unchanged

`git restore <file_name>`: discard changes that haven't been staged

`git commit .`: 



