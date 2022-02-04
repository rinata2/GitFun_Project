# git push

When havea a [remote](./remote.md set up you'll need to begin to move[commits](./commit.md) to the remote. This can be done with the command`git push`.

You can attach a name and branch name to your command to specify where you're pushing to.

```
git push origin main
```

This command will push the **main** branch to the remote called **origin**. This means any commits are in your local will be **pusched **to the remote. 

### Upstream Tracking

Instead of including the name of the remote and the branch you're on every time, you can set local braches to track an upstream branch. This means you can tell the brach to push to its assigned upstream remote branch by usin the comman `git push`.

Before doingso, you'll need to use the `u` or `--set-upstream` flag. this can be done on any `git push`.

```
git push -u origin main
```

After this command is used, you can just use `git push` and it will function the same way. 

## Resources 

- [Git Congfig Documentation](https://git-scm.com/docs/git-push)

---

[Back to home](../)
