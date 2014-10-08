remotesquashexample
===================

This will show how to push a lot of commits, then squash them remotely

The main command is

git rebase -i FROM TO

In other words

If you are using master

git rebase -i master~5 master

Were you using, develop
then replace master with develop

There will be some deletions, and typo fixes, like this here

More lines

33
more
more
more
more
