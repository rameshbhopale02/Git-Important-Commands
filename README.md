# Git-Important-Commands
Git Imp Commands
Steps to deploy project or upload project over github
<br>
1. Clone a Repository : git clone "repository-link"
2. Change Directory to repository folder : cd /currentFolder
3. Create a New Branch : git branch new-feature
4. Switching to new Branch : git checkout new-feature
5. Make Changes and Commi : git add <filename> or git add . (adding all files in current repo)
6. Push the Branch to the Remote Repository : git push origin new-feature
7. Create Pull request : To move the tempory used branch data to main branch
   <br>
Repository Creation and Management:
•	git init - Initializes a new Git repository.
•	git clone <url> - Creates a local copy of a remote Git repository. (Replace <url> with the actual URL of the remote repository.)
•	git add <file> - Stages changes in a file for commit.
•	git commit -m "message" - Commits staged changes to the local repository with a message. Enclose the message in quotes.
•	git status - Shows the current status of the working directory and staging area.
•	git log - Displays the commit history.
Branching and Merging:
•	git branch <name> - Creates a new branch named <name>.
•	git checkout <name> - Switches to a different branch named <name>.
•	git merge <name> - Merges changes from branch <name> into the current branch.
•	git branch -d <name> - Deletes a local branch named <name>. (Use with caution!)
•	git branch -r - Lists remote branches.
Remote Repositories:
•	git remote add <name> <url> - Adds a remote repository named <name> with the URL <url>.
•	git remote -v - Lists remote repositories.
•	git push <remote> <branch> - Pushes changes in the current branch to the remote repository named <remote>.
•	git pull <remote> <branch> - Fetches changes from the remote repository named <remote> and merges them into the current branch.
Other Useful Commands:
•	git diff - Shows differences between files.
•	git reset --hard <commit> - Resets the current branch to a specific commit (use with caution!).

