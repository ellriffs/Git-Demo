# GIT DEMO
- A simple repo for practicing git commands
- use this demo to get used to dealing with PR reuests and merge conflicts

### Happy Coding

## Git Cheats for single commits using -p flag

**git add -p**

-          y - stage this hunk
           n - do not stage this hunk
           q - quit; do not stage this hunk nor any of the remaining ones
           a - stage this hunk and all later hunks in the file
           d - do not stage this hunk nor any of the later hunks in the file
           g - select a hunk to go to
           / - search for a hunk matching the given regex
           j - leave this hunk undecided, see next undecided hunk
           J - leave this hunk undecided, see next hunk
           k - leave this hunk undecided, see previous undecided hunk
           K - leave this hunk undecided, see previous hunk
           s - split the current hunk into smaller hunks
           e - manually edit the current hunk
           ? - print help

## Other Commands

- git status
show modified files in working directory, staged for your next commit
- git add [file]
add a file as it looks now to your next commit (stage)
- git reset [file]
unstage a file while retaining the changes in working directory
- git diff
diff of what is changed but not staged
- git diff --staged
diff of what is staged but not yet commited
- git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot
