[Hydras](https://github.com/abo-abo/hydra) for [CIDER](https://github.com/clojure-emacs/cider).

## Install

After setting up [MELPA](http://melpa.org/) as a repository, use `M-x package-install cider-hydra` to install the package.

## Setup

Add the following to your init file:

```emacs-lisp
(cider-hydra-on)
```

To turn hydras off, use the `cider-hydra-off` command, which will restore the previous CIDER commands.

## See Also

- The [which-key](https://github.com/justbur/emacs-which-key) package, which
  displays keys following for a prefix key.
