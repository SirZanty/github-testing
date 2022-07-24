# Github-testing

### Move to commit
- git revert <commit to revert>

### Reset from HEAD
- --soft just move to previous commit

- --hard move to previous commit and delete the changes

### Log - Show log history
- git log --all --graph --decorate --oneline

### Tag
- git tag -a "TagName" -m "Mensaje"  * Add tag to local
- git push --tags * Push tags to github
- git tag -d "Nombre del tag" * Delete local tag
- git push origin :refs/tags/nombre del tag * Delete tag on github

### Switch to other branch - alternative to checkout
- git switch "branch"

### Git Checkout - split into 2 commands
- git switch
- git restore file | restore file - discard changes
- git restore --staged -- "file" | restore from stage (restore after add)

# Grep

### Find text in forder linux
- grep -rnw 'path' -e 'pattern'

# Find

### Find files
- find /etc -type f File type
- sudo find /etc -mtime 10 Modify last 10 mins
- find /var/log -name '*.log' -type f Find files with .log extension
- find /var/log -iname '*.LOG' -type f Find files .log extensions with upper or lower case.

# AWK

### Information process
- awk '{print $1}' /pathfile Get first column
- awk '{print $1}' /pathfile | sort | uniq -c Get first column, sort and get uniq

