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
<br>
git init: Initializes a new Git repository in the current directory.
<br>
git clone <url>: Creates a local copy of a remote Git repository.
<br>
git add <file>: Stages changes in a file for commit.
  <br>
git commit -m "message": Commits staged changes to the local repository with a message.
  <br>
git status: Shows the current status of the working directory and staging area.
  <br>
git log: Displays the commit history, including author, date, and commit message.
  <br><br>
Branching and Merging:
<br>
git branch <name>: Creates a new branch.
  <br>
git checkout <name>: Switches to a different branch.
git merge <name>: Merges changes from one branch into another.
git branch -d <name>: Deletes a local branch.
git branch -r: Lists remote branches.
Remote Repositories:

git remote add <name> <url>: Adds a remote repository.
git remote -v: Lists remote repositories.
git push <remote> <branch>: Pushes changes to a remote repository.
git pull <remote> <branch>: Fetches changes from a remote repository and merges them into the current branch.
Other Useful Commands:

git diff: Shows differences between files.
git reset --hard <commit>: Resets the current branch to a specific commit.
git revert <commit>: Reverses a commit.
git stash: Saves the current working state temporarily.
git stash pop: Restores the most recently stashed state.
git checkout -- <filename>: Discards changes to a specific file.
git rm <filename>: Removes a file from the repository.
git mv <oldname> <newname>: Renames a file or directory.
git tag <name>: Creates a tag for a specific commit.
git show <tag>: Displays information about a tag.
