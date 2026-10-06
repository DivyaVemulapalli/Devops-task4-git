# DevOps Task 4 - Git Version Control

## Project

This project demonstrates Git and GitHub best practices, including branching, commits, pull requests, merge conflict resolution, Git stash, `.gitignore`, and Git tags.

## Objective

This project demonstrates Git and GitHub version control best practices, including branching, commits, pull requests, merge conflict resolution, Git stash, `.gitignore`, and Git tags.

## Git Workflow

The project follows this workflow:

```text
feature → dev → main
```

* `feature` branch: Used to develop new changes.
* `dev` branch: Used to integrate and test changes.
* `main` branch: Contains the final stable version.
* Pull requests are used to review and merge changes between branches.

## Pull Requests

Two pull requests were used in this project:

1. `feature` → `dev` — added Git workflow documentation.
2. `dev` → `main` — promoted the completed project to the main branch.

Pull requests were used to review and merge changes between branches.

## Merge Conflict Resolution

A merge conflict was intentionally created by modifying the same line in a temporary feature branch and the `dev` branch.

The conflict was resolved by:

1. Checking the conflicted files using `git status`.
2. Opening `README.md` and reviewing the conflict markers.
3. Keeping the correct version of the content.
4. Running `git add README.md`.
5. Committing the resolved merge.

This demonstrated how Git conflicts can be identified and resolved safely.

## Git Stash

Git stash was used to temporarily save uncommitted changes.

Commands practiced:

```bash
git stash
git stash list
git stash pop
```

The change was restored using `git stash pop` without creating a commit.

## .gitignore

The `.gitignore` file prevents unnecessary or sensitive files from being tracked by Git.

The project ignores:

* `node_modules/`
* `.env`
* `*.log`

## Git Tags

An annotated Git tag was created for the final project version:

```text
v1.0.0
```

The tag was pushed to GitHub to mark the release version.

## Tools Used

* Git
* GitHub
* Visual Studio Code

## Outcome

This project demonstrated a practical Git and GitHub workflow using branches, commits, pull requests, merge conflict resolution, Git stash, `.gitignore`, and Git tags.

The final project was merged into the `main` branch and tagged as `v1.0.0`.

