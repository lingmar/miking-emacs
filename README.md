# miking-emacs
This repo contains an Emacs mode for editing
[Miking](https://github.com/miking-lang/miking/) code
(MCore/MLang). Pull requests and issue reports are welcome!

To use the mode, add the following to your `init.el` file:

```
;; MCore mode
(add-to-list 'load-path "/path/to/miking-emacs/")
(require 'mcore-mode)
```

(or run `M-x eval-buffer` in the file defining the mode)

## Companion Packages

- [Ctags support](https://github.com/miking-lang/miking-ctags)