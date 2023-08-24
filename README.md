# git-hooks-ctags

These scripts are adapted from a post by tpope, [Effortless Ctags with Git][1].
To use these hooks, place them in the repository's `.git/hooks/` directory. They
can also be used as a plugins by running [this git-hooks script][2] to set up
symlinks for each git hook and then cloning the repository to one of the
following directories:

- ~/.config/git/hooks/plugins/git-hooks-ctags (for global plugins)
- .git/hooks/git-hooks-ctags (for local plugins)
- .githooks/git-hooks-ctags (for local plugins that can be committed)

[1]: https://tbaggery.com/2011/08/08/effortless-ctags-with-git.html
[2]: https://git.sr.ht/~rasch/containers/blob/main/git/scripts/git-hooks
