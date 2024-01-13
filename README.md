# labtwo
version control lab 2

# Delete dev branch locally
git branch -d dev

# Delete test branch locally
git branch -d test

# Delete dev branch remotely
git push origin --delete dev

# Delete test branch remotely
git push origin --delete test

# List all tags locally
git tag

# Delete the tag locally
git tag -d v1.4

# Delete the tag remotely
git push origin --delete v1.4

What is git rebase?
git rebase is a command used to integrate changes from one branch into another. It is often used to maintain a clean and linear project history. Unlike git merge, which creates new commit objects for the merge, git rebase moves or combines a sequence of commits to a new base commit.

Example of git rebase:
Suppose you have a feature branch named feature_branch and you want to rebase it onto the main branch.

# Switch to the feature branch
git checkout feature_branch

# Rebase feature_branch onto main
git rebase main

Pull Request:
A pull request is a way to propose changes to a repository. It notifies others about changes you've pushed to a branch in a repository on GitHub. Others can review the changes, discuss potential modifications, and even push follow-up commits if needed.

