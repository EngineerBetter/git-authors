# git-authors

For use with [https://github.com/git-duet/git-duet](https://github.com/git-duet/git-duet). Allows you to specify who is pairing on a commit using their initials.

Use the following to clone this repo, and create a symlink where `git-duet` expects to find its configuration, pointing to the cloned repo (so you can update it easily).

```shell
# Don't run a command between these two otherwise the symlink won't generate correctly 

# Clone this repo and create symlink to the cloned repo
git clone git@github.com:EngineerBetter/git-authors.git $HOME/workspace/git-authors
ln -s !$/.git-authors $HOME/.git-authors
```
