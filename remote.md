# GIT REMOTE

## View Remote Information
1. ### git remote: 
- This command lists the names of all remotes associated with the current repository.
```bash
git remote
 ```

 2. ### git remote -v
 - Shows the URLs of the remotes for both fetch and push operations
 ```bash
 git remote -v

 ```
## Add a Remote
- To add a new remote to your Git repository
- git remote add <remote-name> <url>: This command adds a new remote with a given name (like origin, upstream, etc.) and the URL of the repository

 ```bash
 git remote add origin https://github.com/username/repo.git

 ```

- origin: This is the default name for the remote repository, but you can choose any name.
- https://github.com/username/repo.git: The URL of the remote repository (it could be SSH or HTTPS).

## Push Changes to a Remote:

- To upload your local commits to a remote repository, use:
```
git push <remote-name> <branch-name>:

git push origin main
```
- Set Upstream Branch (for the first time): If you are pushing a local branch to a remote for the first time, you can set the upstream branch (the remote branch) so that git push can track changes more easily in the future.
```
git push --set-upstream origin my-feature-branch
```

- After this, you can simply use git push without needing to specify the remote and branch.

## Pull from a Remote:
```
git pull origin my-feature-branch
```