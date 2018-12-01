This is a minimal version of
[haskell-mode](https://github.com/haskell/haskell-mode) with just the
stuff I, mgsloan, want. It keeps the highlighting and some of the text
manipulation features of haskell-mode, but removes the complicated
indentation, completion, and interactive mechanisms. This version has
quite a lot less elisp, ~9000 SLOC, whereas haskell-mode currently has
~25000 SLOC.

Not publishing this with the intent to maintain a fork of
haskell-mode. Instead, my motivation to publish this is to be able to
use it as a submodule in my [emacs
config](https://github.com/mgsloan/mgsloan-emacs).

That said, I do think that it would be nice if haskell-mode was
refactored such that it was not so complex, and could drop some of the
legacy stuff. This version of haskell-mode might give an idea of what
a more minimal core might look like.
