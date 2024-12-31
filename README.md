## Tell me how to remove them locally and remotly.
### To delete a remote branch
```git push origin :newbranch```
###  To delete a local branch
``` git branch -d newbranch```
```git branch -D newbranch```
### tell me how to list tags locally.
```git tag```
### tell me how to delete tag locally and remotely.

### To delete a remote tag 
```git push origin --delete v1.4```
```git push origin :refs/tags/v1.4```
### To delete a local tag
```git tag -d v1.4```
### What is git rebase?
integrates changes from one branch into another by replaying commits on top of a base branch, creating a linear history.
It is used to simplify commit history and resolve conflicts while keeping a cleaner project timeline.
