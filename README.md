# one-line-editor
A simple haskell threepenny demo of catching keystrokes, rendering text and using the ffi.

To build this project, type `stack build`.

To run it, type `stack exec one-line-editor`, and then open `http://127.0.0.1:8023/` in a browser.

Then, in the browser, you can type some text, and hit these simple edit keys: left and right arrows, backspace, delete, home and end.

The little blue blob demonstrates that the application knows the width of the text (which is going to be important for writing, say, a word-processor).

To see the signatures etc., type `stack ghci`.
