# git-practice
A repo for myself to practice git operations.

`git clone {url}` : download a repo from Github\
`git clone -b {branchname} {url}` : clone a specific branch from Github

# Commit and Push
`git commit -am "message"` : make a local commit\
`git push` : push the current branch to remote

# Branch
`git checkout -b {local_branch}` : create a local branch\
`git push origin -u {local_branch}` : Publish local branch to remote\
`git checkout {branch_name}` : switch to another branch\

# Merge a branch:
`git checkout main` : go to the branch you want to merge to\
`git merge my_branch` : merge content in my_branch to main


# Delete a branch
Delete a local branch: &nbsp; `git branch -d {name}`\
Delete a remote branch: &nbsp; `git push origin -d {remote_branch_name}` \

