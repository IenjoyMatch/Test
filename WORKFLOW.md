# Git and GitHub workflow

This exercise walks through a small change from a fresh branch to a merged pull request.

1. Update your local default branch: `git switch main` followed by `git pull --ff-only`.
2. Create a descriptive branch: `git switch -c docs/example-change`.
3. Make a focused improvement and inspect it with `git diff`.
4. Stage and commit your changes: `git add <files>` and `git commit -m "Describe the change"`.
5. Push the branch: `git push -u origin docs/example-change`.
6. Open a pull request on GitHub, describe the change, and check its diff and any required checks.
7. Merge when the repository's rules permit it. Update your local `main` afterward.

For another exercise, open an issue that describes a small task, then link it from a pull request using `Closes #<number>`. Avoid committing credentials or private information.
