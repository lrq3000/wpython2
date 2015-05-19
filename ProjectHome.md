WPython is a re-implementation of (some parts of) Python 2.6.4, which drops support for bytecode in favour of a wordcode-based model (where a word is 16 bits wide).

It also implements an hybrid stack-register virtual machine, and adds a lot of other optimizations.

Python 2.6.4 was chosen because it was the "mainstream" version, but the project can be adapted for the new 3.x branch.

WPython is just an experiment, a proof-of-concept for the wordcode model, and the benefits that can be gained using it.