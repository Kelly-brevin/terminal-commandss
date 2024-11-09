#GIT COMMANDS

`git init`
Initializez a new Git repository in the current directory.

`git clone <repository url>`
Creates a copy of an existing Git repository, typically from a remote url, onto your local machine

`git status`
shows the status of changes as untracked, modified, or staged files in the working directory

`git add <file-or directory>`
Stages changes(adds files to the staging area)to prepare for commiting.

`git push`
uploads local commits to a remote repository.

`git fetch`
Downloads changes from a remote repository without merging them into the current branch.

`git merge <branch-name>`
Merges the specified branch into the current branch , combining changes

`git branch`
lists all branches in the epository.
`git branch <branch name>`creates a new branch.

`git checkout <branch-name>`
Switches to a specified branch

`git checkout -b <branch name>`
creates a new branch and switches to it immediately

`git branch -d <branch-name>`
deletes a local branch. use `-d` to force delete if the branch has unmerged changes.

`git tag <tag-name>`
creates a tag (a refernce point) for a specific commit, often marking release points.

`git reset <file>`
Unstages a file that was added to the staging area, moving it back to modified status.

`git remote -v`
lists all configured remote repos and their URL's

`git push <remote> <branch>`
pushes a branch to a specified remote repository eg `git push origin main`
