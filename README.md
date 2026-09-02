# STAT 315 Pull Request Practice

This small public repository is for practicing the collaborative Git and GitHub workflow used in STAT 315:

1. fork this repository on GitHub;
2. clone your fork to your computer;
3. add this repository as the `upstream` remote;
4. create a `dev` branch;
5. make, inspect, stage, and commit one focused change;
6. push `dev` to your fork;
7. open a pull request on GitHub; and
8. review, revise, and merge the pull request.

The original repository is <https://github.com/tamu-stat315/PRdemo-Fall2026>. Students normally cannot push directly to its `main` branch. Instead, you propose a change from the `dev` branch in your own fork.

## Practice task

Add one favorite animal as a new final line in `fav_animal.txt`. Preserve every existing line and do not change any other file.

Before you commit, use `git diff` to check the unstaged change. After `git add fav_animal.txt`, use `git diff --staged` to check exactly what the commit will contain.

## Public-practice reminder

This repository and its forks, commits, pull requests, comments, and usernames are public. Do not include grades, graded work, passwords, access tokens, private datasets, or personal information.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the complete acceptance criteria and pull request procedure.
