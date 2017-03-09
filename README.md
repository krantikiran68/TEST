# TEST_GIT
Repository to Store learning Git commands

BRANCHING

git branch bugFix
git checkout bugFix

Level 3 Merging

git checkout -b branch
git commit
git checkout master 
git commit
git merge branch

Level 4 Rebasing

git checkout -b branch
git commit
git checkout master 
git commit
git checkout branch
git merge master

DETACH YO' HEAD
git checkout <Hash name>

Relative refs
git checkout branch^

GOAL TO REACH
git branch -f master <Hash>
git checkout HEAD^
git branch -f bugFix HEAD^

REVERSING CHANGES IN GIT
git reset local
git checkout pushed 
git revert pushed

Cherry pick
git cherry-pick bugFix side local

Interactive rebase
git rebase -i overHere

Grabbing just one commit
git rebase -i master 
git branch -f master bugFix

Juggling commits 1
git rebase -i master
git commit --amend
git rebase -i master
git branch -f master caption

Jugging commits 2
git checkout master
git cherry-pick C2
git commit --amend
git cherry-pick C3

Git  tags
git tag v0 C1
git checkout HEAD^
git tag v1

Git describe 
git describe

MULTIPLE parents
git branch bugWork HEAD~^2~