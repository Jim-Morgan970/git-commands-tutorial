# Key Git Commands

## Configuring Git

git config --global user.name "Jim Morgan"
git config --global user.email "james_a_morgan@hotmail.com"


## Initializing a Repository

git init


## Cloning a Repository

git clone https://github.com/Jim-Morgan970/repository.git


## Staging and Committing Changes

git add filename
git commit -m "Commit message"


## Viewing History

git log


## Branching

git branch new-branch
git checkout new-branch


## Merging

git merge branch-name


## Deleting Branches

git branch -d branch-name


## Handling Merge Conflicts

# Edit conflicted files
git add resolved-file
git commit


## Stashing

git stash
git stash pop


## Rebasing

git rebase branch-name


## Cherry-Picking

git cherry-pick commit-hash
