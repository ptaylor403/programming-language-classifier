# programming-language-classifier

## What this code should be

### Create a corpus of code snippets with the following languages:
- C (.gcc, .c)
- C#
- Common Lisp (.sbcl)
- Clojure
- Haskell
- Java
- JavaScript
- OCaml
- Perl
- PHP (.hack, .php)
- Python
- Ruby (.jruby, .yarv)
- Scala
- Scheme (.racket)

### Classify new snippets
- Using your corpus, you should extract features for your classifier. Use whatever classifier engine that works best for you and that you can explain how it works. Either using an existing Transformer or one you've written. Be sure you can explain at a high-level how your Transfomer works.

- Write a classifier function that takes a string of code and returns a guess for the language the code was written in. It is recommended you also have a method that returns the snippet's percentage chance for each language in a dict.

### Test the classifier
- The test/ directory contains code snippets. The file test.csv contains a list of the file names in the test directory and the language of each snippet. Use this set of snippets to test your classifier. Do not use the test snippets for training your classifier.
