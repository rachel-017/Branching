## Git Cheat Sheet

A brief reference of git commands

* `git checkout -b otherBranch` - Switch to a new branch 'otherBranch'

* `git init` - Initialize a local git repo in working directory
* `git status` - Show status of local repo
* `git log` - List commit history
* `git log --oneline` - Shows a compact commit history
* `git commit -m "msg" ` - Commit work to local repo w/message
* `git add .` - Stage current directory in git index


### Branching

* `git branch newBranch` - creates local Branch
* `git checkout newBranch` - switches to newBranch

### Remote Repos

* `git remote add alia url` - add `alias` as name for remote repo `url` in project config
* `git push alias aBranch` -push local commits to remote repo `alias`'s branch `aBranch`
