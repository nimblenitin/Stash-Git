# Stash-Git

The git stash command takes your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy.

Simple demonstration-

```

1. Create a new file in a local repo
$ vi demo.txt
$ git status

2. Stash the file
$ git stash
$ git status

3. Re-applying your stashed changes-
$ git stash pop
$ git status

4. Using git stash list to see which stashes you’ve stored
$ git stash list

```
