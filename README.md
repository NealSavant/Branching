## Git Branching

Cheat sheet for git commands

### Basic Git Commands

* `git init` - create local repo
* `git add` - add modified files to index (staging)
* `git commit -m "message"` - commit to local repo
* `git status` - see status of local repo
* `git log` - view commit log
* `git log --oneline` - compact view of commit log
* `git remote add origin URL` - connect local repository to remote URL
* `git `
### Basic Branching

* `git branch` - show branches, current branch
* `git branch branchName` - create branch `branchName`
* `git checkout branchName` - check out the branch
* `git checkout -b otherBranch` - create and checkout `otherBranch`
* `git pull origin otherBranch` - pull remote otherBranch
* `git pull origin master` - pull remote master into local branch to resolve conflicts
* `git push origin otherBranch` - push local branch to Github; go to Github and create pull request
