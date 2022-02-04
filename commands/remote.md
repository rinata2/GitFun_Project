# git remote

When working with git, a **remote** is any git repository htat is not on the machine you're working on. The counterpart to this is **local**, or machine that is being developed on. 

Take GitHub for example. while git is the technology that allows you to create lcoal repositories, GitHub is the site hat will host your reomote repositories. Once stored remotely, you can bring that repository back down or share it with others.

**Note**: while the repositories (local and remote) are related and track the same project,they can have different states if changes are not shared betweeen the two. 

### Addin a remote

A remote can be added with the `git remote add` command, followed by the name and location of the remote.

The name is a local name, meaning it's your labeland does not impace the actual remote whatsoever. 

```
git remote add origin https://github.com/ElevenfiftyAcademy/Gitfun.git
```

### removing a remote

A remote can be removed with the w1git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources 

- [Git Congfig Documentation](https://git-scm.com/docs/git-remote)

--

[Back to home](../README.md)