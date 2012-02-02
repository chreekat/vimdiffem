Running `vimdiffem` in a git repo will load up all files with changes in the
working tree, run Gdiff on the first one, and define commands Go and Gop for
viewing the diffs of the next and previous files. `vimdiffem --cached` does the
same, but examines differences between HEAD, index, and working tree.

*Unless* there are unmerged conflicts, in which case vimdiffem will load up
those!
