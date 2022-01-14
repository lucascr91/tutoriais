### Fetch Pull Request

Run the following command to get the list of PRs and their IDs:

```bash
gh pr list --repo <dono>/<repositorio>
```

Alternatively, you can run just `gh pr list` inside the local repo folder.

#### Forked repo

In a forked repo, you can fetch a PR with ID #123 using:

```bash
git fetch upstream pull/123/head:pr-123
git checkout pr-123
```

#### Repo owned

If the repo belongs to you, you can fetch a PR with ID #123 using:

```bash
git fetch origin pull/123/head:pr-123
git checkout pr-123
```

See also:
[1] https://stackoverflow.com/questions/15397059/how-do-i-get-a-specific-pull-request-on-my-machine#32447815 <br>
[2] https://stackoverflow.com/questions/27567846/how-can-i-check-out-a-github-pull-request-with-git
