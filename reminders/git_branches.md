# Reset branch to origin/branch

```
git fetch origin
git reset --hard origin/branch_name
```

# Deleted branch still appears in repository as origin/branch

```
git fetch -p
```

# Update your branch with the latest changes from another branch

```
git checkout my_feature_branch
git merge main_branch
```