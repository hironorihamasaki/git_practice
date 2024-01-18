Git primarily operates in three different states:

1. Working Directory: Where you make changes to your files.
2. Staging Area (Index): A place to keep changes before they're permanently saved in a commit.
3. Repository (HEAD): Where Git stores saved snapshots of your project.

Here's a list of commands:
- **`git status`**: Tells you what's happening in your working directory and staging area.
- **`git checkout -- .`**: Tosses out all changes made since the last commit in the working directory.
- **`git reset HEAD .`**: Takes any changes you staged and moves them back to the working directory.
- **`git add .`**: Takes all your changes and gets them ready to be permanently saved.
- **`git restore --staged <file_name>`**: "Unstages" a file, or undoes a previous `git add`.
- **`git restore <file_name>`**: Discards changes made to an unstaged file.
- **`git commit`**: Permanently saves your changes. You must include a message with it (like `git commit -m "Your message here"`).
- **`git commit --amend`**: Alters the most recent save or “commit”—either the changes saved in it or the message attached to it.
Sure, I'd be happy to provide some more examples:

- **`git log -p -n`**: Shows the detailed diffs of the last 'n' commits. Replace 'n' with a number. For example, `git log -p -2` shows the changes from the last two commits.

- **`git branch`**: Shows you all of the branches in your repository.

- **`git branch <branch_name>`**: Creates a new branch named `<branch_name>`.

- **`git checkout <branch_name>`**: Switches you over to the branch named `<branch_name>`.

- **`git merge <branch_name>`**: Takes the changes from `<branch_name>` and adds them to your current branch.

- **`git pull`**: Updates your local repository with changes from the remote repository.

- **`git push`**: Uploads your local repository changes to the remote repository.

- **`git clone <repo_url>`**: Makes a local copy of a remote repository given its URL, `<repo_url>`.

- **`git log`**: Displays the commit history in reverse chronological order.

- **`git stash`**: Temporarily saves changes that you don't want to commit right away.

- **`git stash pop`**: Reapplies the changes you stashed away.

Remember that `<branch_name>` and `<repo_url>` are placeholders — you would replace them with the actual name of your branch or the URL of your repository. For example, `git checkout development` would switch to a branch named "development".