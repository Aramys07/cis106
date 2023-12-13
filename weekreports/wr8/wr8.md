---
name: aramys junior tavarez
semester: fall 2023
course: cis106
---

# Week Report 8

## VIM and Nano

### What is VIM?
The vi command-line text editor is included in all POSIX compliant operating system. 

### What is nano?

It is a simple and easy-to-use command-line text editor designed for basic text editing tasks. Nano is particularly popular among users who may be less familiar with command-line editors like Vim or Emacs, as it provides a more straightforward interface.

## VIM functions
To start VIM just write `vim` in the command line.

To quick VIM just press `:q!` and the program will close. 

## VIM modes:
Insert mode: used for writing text.

Normal mode: used for manipulating text.

Command mode: used for entering vim commands.

Visual mode: used for navigation and manipulation of text selections.

Select mode: similar to visual mode.

Ex-mode: Similar to the command-line mode but optimized for batch processing.

## Save a file in VIM
`:w` will save the file.
`:w (file name)` will save the file as the name provided.
`:wq` will save the file and quit.
`:wqa!` will save the file and close all.

## Search in VIM
use / and the word you are looking for to search forward.
`n` will repeat the search for the next word. 
`?` to search backward.
`*` will search for the next occurrence of the word under the cursor.
`#` will search backward for the previous occurrence.

## Delete text in VIM
`dw` to delete current word.
`u` to undo.
`dd` delete line under the cursor.
`d + /word` delete line under the cursor.




