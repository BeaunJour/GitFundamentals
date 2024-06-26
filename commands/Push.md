# git push

When you have a [remote](./Remote.md) set up you'll need to begin to move [commits](./Commit.md) to the remote. This can be done with the command `git push`. 

You can attach a name and branch name to your command to specify where you're pushing to. 

```
git push origin main
```
### Upstream Tracking

Instead of including the name of he remote and the branch you're on every time, you can set local branches to track an upstream branch. This means you can tell the branch to push to its assigned upstream remote branch by using the command `git push`. 

Before doing so, you'll need to use the `-u` or `--set-upstream` flag. This can be done on any `git push`. 

```
git push -u origin main
```
After this command is used, you can just use `git push` and it will function the same way. 

## Resources
- [Git Push Documenation](https://git-scm.com/docs/git-push)

---
[Back to Home](../README.md)

