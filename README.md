boolcase mode
==============

Minor mode to automatically capitalize true and false in languages such as
python. You are able to modify the list of words instead of always just
being true and false.

```lisp
(require 'boolcase)
(add-hook 'python-mode '(lambda () (boolcase 1)))
```

You can modify the list of words to capitalize like this:

```lisp
;; Add hello to list of words to capitalize
(setq boolcase-mode-words (cons "hello" boolcase-mode-words))
```
