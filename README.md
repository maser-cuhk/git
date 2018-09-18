# Project git README.md

# Add User credential
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Download files
git clone "repos.git"

# Check Status
git status
# modified (red) - untracked file but with modification
# modified (green) - tracked file with modification

# Basic Flow
git add "filename"
git commit -m "commit message"
git push origin master

# Git Push - upload changes to remote
git push origin 
#will push changes from all local branches to matching branches the origin remote.
git push origin master 
#will push changes from the local master branch to the remote master branch.
git push origin master:staging 
#will push changes from the local master branch to the remote staging branch if it exists.

# Show difference
git diff "filename"
git diff

# Git Log with user info and full commit id 
git log

# Git lof for short id but without user info
git reflog

# Git GUI interface 
gitk

# Show various types of objects
git show

# git reset
git reset

# Check branch
git branch

# Change branch to another branch
git checkout
