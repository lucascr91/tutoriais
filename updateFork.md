### updateFork

1. Clone your fork repository locally

```bash
git clone <forked-repository>
```

2. Set the original repo as your upstream repo

```bash
git remote add upstream <original repo>
```

Note: In case you don’t know what the origin repo is, you can git to the origin repo folder and type git remote -v

3. Update your local Master to be in synch with the original repo

Assuming if your forked repo master was not altered at all, then you can do the below

```bash
git pull upstream master
```

If you have altered it, you then need to rebase it.

```bash
git rebase upstream/master
```
