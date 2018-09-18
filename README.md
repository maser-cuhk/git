# Project git README.md

# Add User credential
git config --global user.name "Your Name"<br/>
git config --global user.email "you@example.com"<br/>

# Download files
git clone "repos.git"<br/>

# Check Status
git status<br/>
modified (red) - untracked file but with modification<br/>
modified (green) - tracked file with modification<br/>

# Basic Flow
git add "filename"<br/>
git commit -m "commit message"<br/>
git push origin master<br/>

# Git Push - upload changes to remote
git push origin<br/> 
will push changes from all local branches to matching branches the origin remote.<br/>
<br/>
git push origin master<br/> 
will push changes from the local master branch to the remote master branch.<br/>
<br/>
git push origin master:staging<br/> 
will push changes from the local master branch to the remote staging branch if it exists.<br/>


# Show difference
git diff "filename"<br/>
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
