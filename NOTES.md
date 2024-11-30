The Four Areas

+ Warking Area
+ Repository
+ index
+ Stash

Git Objects

+ blob
+ tree
+ commit


HEAD point tos current commit

git rm remove files both from the index and local

git rm --cached filename


git automatically finds out when you're renaming or moving files.


Understanding 'git reset'

Commands That Move Branches

+ commit
+ merge
+ rebase
+ pull


git reset --hard

copy data from the new current commit to both the working area and the index


git reset --mixed


copy data from the new current commit to the index, leave the working area along

git reset --soft 

jost move the branch to new commit

"git reset" moves the current branch, and optionally copies data from the Repository to the other areas


git reset HEAD
git reset --hard HEAD


Breaking into Advanced Workflows

git log  --graph  --decorate  --oneline

git show <branch>
git show HEAD
git show HEAD^
git show HEAD^^
git show HEAD^2
git show HEAD~
git show HEAD~~
git show HEAD~3
git show HEAD^3~2
git show HEAd@{"1 month ago"}


git blame

git log --patch

git log --grep apples --oneline
git log -G apples --oneline
git log -G apples --patch


git log -3 --oneline

git log HEAD~5..HEAD^ --oneline

git log nogood..main --oneline


git submodule add git@github.com/someproject.git

git submodule update --remote --recursive

git submodule init
git submodule update


Three things to Remember About Submodules

+ Think of a submodule is a pointer to another project's commit.
+ Submodule don't changes unless you ask them t of a submodule is a pointer to another project's commit.
+ Submodule don't changes unless you ask them to.
+ If submodule become a chore, look for more powerful Git commands


git subtree








 
