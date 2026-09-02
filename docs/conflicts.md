# Resolving a simple merge conflict

A conflict means Git found overlapping changes and needs a person to decide what the final file should say. Do not choose a side mechanically.

1. Read both versions and restate the intended result.
2. Edit the file so it contains the intended final content.
3. Remove every conflict marker: `<<<<<<<`, `=======`, and `>>>>>>>`.
4. Inspect the file and run `git diff`.
5. Stage the resolved file with `git add FILE_NAME`.
6. Complete the merge with `git commit -m "Resolve merge conflict"`.
7. Run `git status` and inspect the history before pushing.

For a short text-only conflict in a pull request, GitHub's web editor can also be appropriate. For code, multi-file changes, tests, or complicated conflicts, resolve the conflict locally so you can inspect and test the full result.
