# Popular text editors
There are many editors to choose from and they can be grouped into two main categories: _Command-line text editors_ and _GUI text editors_
* **Command-line text editors:**
  * **GNU nano**: a small and friendly modeless text editor
  * **vi**: a traditional command-line editor originally created for Unix
  * **vim**: a powerful mode-based command line-editor based on vi
* **GUI based text editors:**
  * gedit
* **Command-line or GUI**
  * emacs

# GNU nano
## Features of GNU nano
**GNU nano** is a command-like text editor that provides:
* Undo and redo
* Search and replace
* Syntax highlighting
* Indenting groups of lines
* Line numbers
* Line-by-line scrolling
* Multiple buffers

## Using the GNU nano text editor
To open a text file in GNU nano from the command prompt, type: 
```
nano <filename>
```
This opens a new text editor window in which you can edit the file.


Here is what the nano app looks like:
![](/images/nano_1.png)

The main area displays the text of the open file, which in this case is the source text from the nano example page.


The cursor is currently located at the beginning of the file, but you can navigate within the text using the arrow keys, page up and down keys, or `home` and `end` keys. Any text you type is entered at the cursor. You can also delete text using the `Delete` and `Backspace` keys. Pressing `Enter` starts a new line.
![](/images/nano_4.png)


At the bottom of the nano window there is a list of commands that you can use in the editor.
![](/images/nano_5.png)

To access the commands, simultaneously press `control` and the letter for the command. For example, to **Get Help**, press the `control` and `G` keys

# File editing with vim
**Vim** is a traditional and very powerful command-line editor.
To start vim, type:
```
vim 
```
![](/images/vim_1.png)

To specify a file to edit, type:
```
vim <filename>
```

Vim has two basic modes: **Insert mode**, where you enter text, and **Command mode**, where you do everything else.

**Insert mode:**
* Press `i` to enter Insert mode
* Type some text
* Press `Ecs` to exit Insert mode and switch to Command mode
* The text is written to the buffer at the cursor location

**Command mode:**
* Enter: `:sav example.txt` to create a file and write the buffer to the file
* Enter: `:w` to write the buffer to the file without exiting
* Enter `:q` to quit vim session
* Enter `:q!` to quit without saving
