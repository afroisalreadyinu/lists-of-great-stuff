# Command line software

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