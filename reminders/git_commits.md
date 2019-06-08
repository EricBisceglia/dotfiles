# Edit the title of a pushed commit (rewriting history)

```
git rebase -i HEAD~3
```

Replace "pick" with "edit" for the guilty commit.

```
git commit --amend
git rebase --continue
git push --force origin branchname
```