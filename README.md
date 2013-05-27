# Git Changelog

Display the changes since the last Git tag if tags exist, otherwise show all changes.


## Installation

Symlink `git-changelog` to somewhere in your `PATH`, then run `git changelog` from a Git repository.


## Usage

Any arguments will be passed to `git log`.  The `--no-merges` flag is always passed.  If you want to quote any strings in the arguments, you must escape the quotes.  For example:

```
git changelog --pretty=format:\"%an %h %s\" --graph
```
