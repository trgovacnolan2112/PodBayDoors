# Git Remote   
When working with git, a **remote** is any git repository that is not on the machine you're working on. the counterpart to this is **local**, or the machine that is being developed on.
Take GitHub for example. While git is the technology that allows you to create local repositoreis, GitHub is the site that will host your remote repositories. Once sotred remotely, you can bring that repository back down or share it with others.
**Note**:While the repositores (local and remote) are related and track the same project, they can have differnt states if changes are not shared between the two
### Adding Remote
A remote can be added with `git remote add` command followed b the name and location of the remote. the name is a local name, meaning its your label and does not impact the actual remote whatsoever
```
git remote add orgin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```
### Removing a remote
A remote can be removed with `git remote remove` command, followed by the name of the remote.
```
git remote remove origin
```
## Resources
- [Git Remote Documentation](https://git-scm.com/docs/git-remote)
---
[Back to Home](../README.md)