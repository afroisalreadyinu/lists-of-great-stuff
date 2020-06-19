# Command line software

- [entr](http://eradman.com/entrproject/) is a very simple utility that runs a
  command when a file in a give list of files changes. In order to run all tests
  with `pytest` when a code file changes, for example, you would run `find .
  -name '*.py' | entr 'pytest'`.

- [file](https://en.wikipedia.org/wiki/File_(command)) is one of those utilities
  that you need once every few months, but then it's exactly the right thing.
  `file` prints detailed information on the type of a file; what kind of an
  executable it is, which encoding a text file has etc, which pdf version etc.

- [fzf](https://github.com/junegunn/fzf/) is a freakishly fast interactive file
  finder. It does fuzzy match, so typos are not a problem. Much better then
  fiddling around with `find` options.

- [jq](https://stedolan.github.io/jq/) makes it possible to carry out complex
  queries and transformation on JSON on the CLI. Great for scripting APIs.

- [ps2pdf](https://linux.die.net/man/1/ps2pdf) is a utility for converting
  Postscript to PDF. In itself this is not exciting, but coupled with the good
  old ~man~ command producing Postscript, this means that you can convert man
  pages to PDF. In order to save the ~systemd~ man pages as PDF, for example,
  you would need to run ~man -t systemd | ps2pdf - systemd.pdf~.

- [unp](https://github.com/mitsuhiko/unp) is a tool that unpacks archives. It
  recognizes archive type from suffix and uses the right CLI tool to unpack it.
  Can be installed on ubuntu with `apt install unp`.