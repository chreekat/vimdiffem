Running `vimdiffem` in a git repo will load up all files with changes in the
working tree, run Gdiff on the first one, and define commands Go and Gop for
viewing the diffs of the next and previous files.

*Unless* there are unmerged conflicts, in which case vimdiffem will load up
those!

You can also specify what to diff against (e.g. "HEAD^^") as a command line
argument.

TODO
----

* Now that I know about :redir and the :arg\* commands, use those to make
  `vimdiffem` available from an existing session, allowing a restore of existing
  arglists!
