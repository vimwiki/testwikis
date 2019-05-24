# Vimwiki Test Wikis

This repository contains sample wikis for testing and development purposes.

## Minimal vimrc

A minimal `vimrc` is also available which contains basic setup for 3 wikis, one
for each Vimwiki syntax. To use, update the paths, add any settings needed for
testing and then invoke vim with: `vim -u minimal_vimrc`.

Use `git update-index --skip-worktree minimal_vimrc` to tell git to ignore any
local changes to the minimal vimrc. To revert this change run
`git update-index --no-skip-worktree minimal_vimrc`
