# Basic git commands

### add
git add <file1> <file2>	
- Adds <file1> and <file2> to the staging area.

git add *.py
- Adds all python files in the current directory to the staging area.

### status
git Status	
- Lists changes in working directory, and staged files.

### commit
git commit
- Records everything in the staging area to your repository. The default text editor will prompt you for a commit message.

git commit -m "Commit message"
- Records everything in the staging area to your repository with the commit message "Commit message"

git commit --amend
- Modify last commit instead of creating a new one. Useful for fixing small mistakes.

### push
git push
- Incorporates changes from local repo into origin.

git push <repo> <branch>
- Incorporates changes from local repo into <repo> <branch>

### log
git log
- Prints commit history of repo.

git log <filename>
- Prints commit history of <filename>.