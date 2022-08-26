## Vocabulary
- Buffer
- Minibuffer


Timeless Technologies
- Natural language
- Math
- Logic
- Command line interface
- Nano
- vi
- Make
- Emacs
- MySQL
- HTML
- CSS
- Markdown
- JSON
- plain text, text processing
- a lisp (go with Clojure)

Emacs is a Lisp Interpreter
keystrokes are bound to commands


Emacs Commands
- C-g is exit/escape hatch for commands
- C-x b opens the minibuffer to create or select buffers
- C-x C-f  to open a file or create a file
- C-x C-s saves a buffer to file (mac + s works, too)
- C-x b binds to switch-to-bufffer (create or selects a buffer)
- letters and numbers on their own run the function self-insert-command
- C-x C-s is bound to save-file
- M-x runs the smex command (run commands by name). Try M-x then running smex.
- C-h pulls up the emacs tutoral
- C-k kills text after the point
- C-/ is undo, your normal OS keybinding for undo should work, too.
- C-a moves you to the beginning of the line
- M-m moves your point to the first non-whitespace character on the line
- C-e moves to the end of the line
- C-f moves forward one character
- C-b moves backward one character
- M-b moves you back one word
- M-f moves you forward one word
- C-s brings up Regex search for text in the current buffer and moves to it. 
- C-s again moves to the next match
- M-g g goes to a specified line
- C-r is same as C-s regex search but in reverse
- M-< moves to the beginning of the buffer (means use SHIFT)
- M-> moves to the end of the buffer (means use SHIFT)

## Emacs Modes
- a mode is a collection of key bindings and functions packaged together to help w/ editing different types of files
- major and minor mods
- clojure and markdown are major modes


## Questions
- how to check what function a key binding is bound to
- how to setup up my own keybindings


C-l center screen and redisplay text (top, middle, bottom)
C-v page down, fn-down
M-v page up, fn-up
M-< top of document, fn-left
M-> bottom of document, fn-right

M-x then run shell. 

See https://www.reddit.com/r/emacs/comments/wx11fl/the_email_that_made_me_convert_to_emacs/
"""The customization you can do in VSCode, or any other environment, stands in relation to that which can do in emacs as the sounds you can coax from a referee's whistle stand in relation to the music you can play on a piano.

But that's not the point. The point is that everything is a buffer -- EIAB. Until one has used emacs enough for that to sink in, one has not really used it, and one might as well stick with VSCode. Pick your favorite shell (bash, zsh, etc.) and make it your default shell in emacs. Then do M-x shell. Start using your new shell. Observe that it is just another buffer. Live with that for a while, until the profundity of it sinks in. Then accept your fate, which is to watch in pity, for the rest of your life, as your non-emacs colleagues struggle to interact with their computers. You're now a deer bounding through the woods, past coyotes chewing their own legs off from the traps they're stuck in. Unfortunately, you can never unsee that vision. Sorry!"""


Data processing
Text processing
Computation
Command line above and beyond Windows Explorer/Finder functionality, piping streams, everythign is a file.



