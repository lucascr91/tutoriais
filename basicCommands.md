## Basic Commands

#### Status:

Compare current folder with remote repo

```bash
git status
```

#### Branches:

Check current branch:

```bash
git branch
```

The current branch is the starred one

Switch to branch "hello":

```bash
git checkout hello
```

Add commit to existing PR:

```bash
git commit -m "These changes are in response to PR comments"
git push -f origin HEAD
```
