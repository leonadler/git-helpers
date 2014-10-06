## git-delete-branches

Deletes multiple branches easily by editing a text file.

Usage: `git delete-branches`

### Background

If you work in a review-oriented git workflow, you end up having a lot
of open branches dangling around. To delete many branches from the
command line you need type a lot of commands. In the most git GUIs,
you would need to confirm the deletion of every branch.
To make this process faster for "git pros", this script can be used.

### Functionality

1. Run `git-delete-branches` on the command-line or via your GUI
2. An editor window/tab with your current branches opens up
3. Remove or comment lines to delete the branches with the same name
4. Save the file and exit your editor to make the changes

### Configuring your editor

By default, git will open vim to edit files during commit, rebase, etc.
If you are not used to vim or prefer a different editor, you can change it by
editing a configuration setting (core.editor).

As an example, to change the default editor git uses to Sublime Text (Windows):
> `git config --global core.editor '"C:/Program Files/Sublime Text 3/sublime_text.exe" --wait'`
