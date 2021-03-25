# git-authors

For use with [https://github.com/git-duet/git-duet](https://github.com/git-duet/git-duet). Allows you to specify who is pairing on a commit using their initials.

Use the following to clone this repo, and create a symlink where `git-duet` expects to find its configuration, pointing to the cloned repo (so you can update it easily).

```shell
# Clone this repo
git clone git@github.com:EngineerBetter/git-authors.git $HOME/workspace/git-authors
# Create symlink to the cloned repo
ln -s !$ $HOME/.git-authors
```
