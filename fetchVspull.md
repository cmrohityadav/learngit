# fetch
- git fetch downloads changes (new commits, branches, tags) from a remote repository to your local repository without merging those changes into your working directory.
- It updates your local copy of the remote branches (e.g., origin/main, origin/feature-branch) but does not affect your current branch or the working directory.
- You use git fetch when you want to see what changes have been made in the remote repository without affecting your local code. This allows you to inspect the changes before merging them into your working branch.

```
git fetch origin

```
- This will fetch all the updates from the origin remote but won't change your working directory.

- When you want to check for new changes or branches in the remote repository but don't want to immediately merge them into your current branch.
- Useful if you want to review changes first, for example, by checking out a specific branch from the remote or viewing the differences.

# git pull
- git pull is essentially a combination of two commands: git fetch followed by git merge (or git rebase, depending on your configuration).
- It first fetches the latest changes from the remote repository, and then merges those changes into your current local branch.

- If there are conflicts, Git will prompt you to resolve them before completing the merge.

- You use git pull when you want to fetch the latest changes and automatically merge them into your current branch. It’s a convenient way to stay up to date with the remote repository without having to manually fetch and merge separately.
```
git pull origin main
```