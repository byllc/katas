#### OSX Terminal

This Kata can be run in the MacOS terminal and many of the commands also work in editors like Atom.io

Moving:
  * Option/Alt + Left/Right: Move one word left or Right
  * Control + W : Delete word before cursor
  * Escape + T : Swap the previous two words
  * Control + T : Swap the last two characters
  * Command + A : Jump to the front end of the line
  * Command + E : Jump to the back end of the line
  * Control + U : Clears the line preceding the cursor
  * Command + K : Clear the entire terminal screen
  * Escape + B : move back by one word
  * Escape + F : move forward by one word
  * Control + H : Backspace
  * Command + Left : move to end of line
  * Command + right : move to beginning of line

Selecting:
  * Shift + Command+ Left : Select text to beginning of a line  
  * Shift + Command + Right: Select text to end of a line
  * Shift + Option + Right: Select text to beginning of word
  * Shift + Option + Right: Select text to end of current word
  * Shift + Command + Up: Select text to beginning of all text
  * Shift + Command + Up:  Select text to end of all text


### Kata
Start with the beginning statement and progress through to each
iteration progressively. Try to do it in fewer commands than the suggested approach


`The quick brown fox jumps over the lazy dog`


- `The brown quick fox jumps over the lazy dog`
  - esc + a, alt + >, alt + >, alt + >, esc + t


- `The brown quick fox jumps the lazy dog`
  - esc + e, alt + <, alt + < , alt + <, ctrl + w


- `dog The brown quick fox jumps the lazy`
  - ctrl + e, shift + alt + <, ctrl + c, ctrl + a, ctrl + v


- ` The dog brown quick fox jumps lazy the`
  - ctrl + e, esc + t, ctrl + a, shift + alt + >, cmd + x, alt + >, cmd + v

... TBC  
