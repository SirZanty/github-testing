# github-testing

### Move to commit
git revert <commit to revert>

### Reset from HEAD
- --soft just move to previous commit

- --hard move to previous commit and delete the changes

### Log - Show log history
- git log --all --graph --decorate --oneline

### Tag
- git tag -a "TagName" -m "Mensaje"  * Add tag to local
- git push --tags * Push tags to github
- git tag -d "Nombre del tag" * Delete local tag
- git push :refs/tags/nombre del tag * Delete tag on github
