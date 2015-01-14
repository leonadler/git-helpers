## git-ls-deleted

Show deleted files of a folder in the git history.

Usage: `git ls-deleted [<path>]`

### Background

To recover versioned files that were deleted in history, you need
to know which files existed before. Using `git blame` or `git-log`
on a file that does not exist at your current commit does not work.
In order to make finding deleted files more comfortable for
command line users, this script can be used.

### Functionality

Run `git ls-deleted` on the command-line to list the files
that were deleted in the current directory.
Run `git ls-deleted <relative path>` on the command line to only list
files that were deleted in a specific folder.
