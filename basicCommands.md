## Basic Commands

#### Status:

Compare current folder with remote repo

```bash
git status
```

#### Branches:

Create a branch:

```
git branch feature
```
where ``feature` is the name of the new branch

The above command creates the new branch but keep the user in the master branch. To switch to branch "feature":

```bash
git checkout feature
```

If you want to create a new branch and enter into it right away type:

```bash
git checkout -b feature
```

Delete a branch:

To delete a merged branch locally:

````bash
git branch -d <branch-name>
```

To delete an unmerged branch locally:

````bash
git branch -D <branch-name>
```

To delete a branch remotely:

```bash
git push --delete <remote name> <branch name>
```

Check branches:

```bash
git branch -a
```
The current branch is the starred one

To merge a branch into master, go to the master branch and type:

```bash
git merge feature
```
#### PR:

Add commit to existing PR:

```bash
git commit -m "These changes are in response to PR comments"
git push -f origin HEAD
```
