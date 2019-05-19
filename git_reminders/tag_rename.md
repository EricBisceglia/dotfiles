# Renaming a git tag

git tag new_tag_name old_tag_name
git tag -d old_tag_name
git push origin :refs/tags/old_tag_name
git push --tags