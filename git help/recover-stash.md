# Git - Recover dropped stash

If you didn't close the terminal, look at the hash of the dropped commit from the log line of the drop command.
It should look like this: `Dropped refs/stash@{0} (2ca03e22256be97f9e40f08e6d6773c7d41dbfd1)`

Just do the following to recover the stash of use the created branch to cherry pick your commit

```
git branch tmp 2cae03e
git stash apply tmp
git stash
```
