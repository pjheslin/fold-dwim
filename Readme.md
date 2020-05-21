# fold-dwim.el

Emacs has a number of different text folding mechanisms, each with their own commands to fold and unfold.  This package attempts to provide a unified interface.

DWIM stands for "do what I mean", as in the idea that one keystroke can do different things depending on the context. In this package, it means that, if the cursor is in a currently hidden folded construction, we want to show it; if it's not, we want to hide whatever innermost folding construct the cursor is in, regardless of type.
