# git commands

[Git .MD Format](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

### To rebase one branch with the main (sync):
```git
git checkout [branch-name]
git fetch
git rebase main
git rebase --continue
git push --force origin [branch-name]
```

### After the rebase, commit and push the changes as a SINGLE COMMIT from the branch to main
```git
git checkout main
git merge --squash [branch-name]
git commit -m "commit name"
git push origin main
```

### Command git to merge current changes with the last commit.
(use git bash)
```git
git commit --amend --no-edit && git push --force
```