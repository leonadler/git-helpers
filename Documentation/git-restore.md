## git-restore

Restore a deleted file from git history

Usage: `git restore [<filepath>]`

### Background

From time to time, you may want to recover a file that was deleted somewhere
along the way in the git history.
With native git you would need to know at which revision the file
still existed and then use `git checkout` to restore it.
This script automates these two steps.

### Functionality

Run `git restore <filepath>` on the command-line to restore the last state of a deleted file.
