# Git Notes

## Intro

Git is the foundation of how teams ship code

Version control - tracks changes to code over time, see who changed what

Terraform files, modules, Kubernetes, Ansible etc files live in Git - so you can make change there.

SVN - single, central server - if it went down, could not commit, had to lock files when editing, merge conflicts common.

Git - distributed copies - resilient to outages, can work offline, everyone can commit

Git is not just a file tracker - holds whole repo

.git directory holds everything git needs to function

split into different folders for different purposes

## Common commands:

git init - initialises a new Git repo with .git directory

git add - stages changes

git commit - snapshot changes

git status - show staged/unstaged work

git log - show commit history

git diff - show what changed

git config - set user/email

git help <command> - built-in docs

git clone - copy a remote repo

git rm - remove files

git mv - rename files

git restore - undo file changes




