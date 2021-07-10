## git branch
## git logs
## git checkout [branch name]

## In master branch, git merge [feature branch]
## better approach, also in master branch
git merge --squash [feature branch]
git commit -m "message"


## git rebase
In feature branch
git rebase [master branch]
result in feature branch latest commit rebased on master latest commit 
## if conflicts
Once you’ve resolved the conflict, you git add your changes to the commit and run git rebase --continue to continue the rebase process.