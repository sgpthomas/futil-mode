# Futil Mode
This provides simple syntax highlighting and indentation for Futil in Emacs.

## Installation
Clone this repository to a location of your choice. Add it to the laod path, and then require `futil-mode`.
In your emacs config, put something like the following:
```elisp
(push "~/.emacs.d/private/local/fuse-mode" load-path)
(require 'fuse-mode)
```

## Known Bugs
 - The indentation code isn't aware of comments which means that a lone bracket in a comment will throw off indentation.
 - Negative numbers not highlighted
