##Git Cheatsheet

###Basic commands
* `git init` - Initialize local git repository
* `git status` - show status of working directory
* `git add` - Add everything in current directory to git index
* `git commit -m"some message"` - Commit current work to local repository
* `git log` - Show git commit history
* `git log --oneline` - show git history (compact)

### Branching commands
* `git branch` - Lists branches in current repository
* `git branch someBranch` - create branch `someBranch`
* `git checkout someBranch` - move to branch `someBranch`
* `git checkout -b otherBranch`- create and checkout `otherBranch`
* `git pull origin main` - pull remote `main` into current branch
### Remote commands
* `git remote add origin URL` - set remote repo alias `origin` for `URL`
