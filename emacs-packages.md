- [fiplr](https://github.com/kevinkehl/fiplr) is an interactive
  file fuzzy-finder. If you are looking for a file in a deep
  directory hierarchy, you can use this mode to get to it with a
  keyword in its name.

- [ido](https://www.gnu.org/software/emacs/manual/html_mono/ido.html) is a
  wonderful tool that helps you navigate commands and files interactively,
  instead of having to type complete paths. It comes with later versions of
  Emacs; enabling it is very easy; it's enough to put the following in your init
  file:

```
    (require 'ido)
    (ido-mode t)
```

- [magit](https://magit.vc/) is an excellent package that brings the best out of
  Emacs. Calling it a package is not fair, in fact, because magit is a complete
  Git client written in Elisp. It integrates perfectly with the design of Git
  and the features of Emacs, enabling a very quick and precise workflow. Once
  you get used to it, it's very difficult to use anything else.