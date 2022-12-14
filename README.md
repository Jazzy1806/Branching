## Git and Git Branching Cheat Sheet

### Basic Commands
* 'git init'  - create initialize current directory with repository

* 'git add .' - add all new or changed files in current directory to git index, staging them for commit

* 'git commit -m "some message' - commit staged changes to local repository


### Info comamnds
* 'git status' - show status of current working directory
* 'git log' - list commit history
* 'git log --oneline' - list commit history (compact)
* 'git config -l' - list local git configuration settings

### Branch Commands
* 'git branch' - shows which branch you're in
* 'git branch newBranch' - creates a new branch in the repository called "newBranch"
* 'git checkout newBranch'- switches to allow you to work from newBranch
* 'git checkout main' -  switch back to working from main Branching

* 'git checkout -b otherBranch' - switch to branch "otherBranch", creating it if it doesn't exist

### Other Commands
* 'git help' - list git subcommands and options
* 'git config --help' - show options for 'git config'


### Remote Commands
* 'git remote add origin someURL' - connect local repo to remote repo url as 'origin'
* 'git push origin branchName' - push local commites to remote repo into branch 'branchName'
* 'git pull origin branchName' - pull remote branch into local current branch
* 'git pull origin main' - pull main into your branch you've been workin on so minimize merge conflicts.
