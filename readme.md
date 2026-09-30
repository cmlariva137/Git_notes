## Git Notes:

Highlight text and right click in terminal to copy 

```
git init											# Makes current folder a repo
git add <fileName>									# Stage one file
git add -A											# Stage all files
git commit -m "<msg>"								# Commits all changes
git checkout -b <branchName>						# Creating new branches
git checkout <branchName>							# Switching between existing branches
git status											# Check for current branch or uncommited changes
git merge <branchName>								# Merges changes from one branch to your current branch
git tag -a "<version>" -m "<message>"				# Adds a tag to current commit
git log												# Shows history of commits
git reflog											# Shows the last 15 git commands
git blame											# Shows who commited what line
git diff											# Shows the difference between commits
git reset --hard <optional id>						# Go back in time
git remote add <origin> <url>						# One time connection to github
git push origin <branch>							# Sync the remote/origin to local changes
git pull origin <branch>							# Sync the local to remote/origin changes
```