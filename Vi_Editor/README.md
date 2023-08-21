# Mastering Vi: A Brief Guide to well start

Vi, a versatile and efficient text editor, has been a popular choice for coding and text manipulation for decades. It is the easiest editor when you have to write code in commande line. Vi is free under the [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.html#license-text) and is available for Windows, Linux, and Mac OS. You might search **vim**. 😊 I had the fortunate experience of discovering Vi during my tenure as a software engineer. In this concise guide, I'll introduce some common Vi commands that will help you navigate this editor with confidence 😉

## Installation and Initial Steps

Before diving into commands, ensure you have Vi installed. You can typically find it pre-installed on most Unix-like systems. To start using Vi, simply open your terminal and type `vi` followed by the name of the file you want to edit. Here's how to get started:

1. **Opening and Creating Files:**
   - To open a file: Type `vi filename`.
   - To create a new file: Type `vi new_filename`.

2. **Basic Navigation:**
   - Move the cursor: Use `h` (left), `j` (down), `k` (up), and `l` (right) keys.

3. **Saving and Quitting:**
   - Save: Press `Esc`, then type `:w` and hit `Enter`.
   - Save and Quit: Press `Esc`, then type `:wq` and hit `Enter`.

## Efficient Editing

Vi's power comes from its efficiency in text manipulation. Here are some commands to enhance your editing prowess:

1. **Inserting Text:**
   - To start inserting text: Press `i`. This will switch you to insert mode, allowing you to add or edit text directly.

2. **Exiting Insert Mode:**
   - To exit insert mode and return to command mode: Press `Esc`. This will save any changes you've made and allow you to execute commands again.

3. **Cut, Copy, Paste:**
   - Cut: Position the cursor, type `dd` to delete the line, or use `d` followed by a movement command.
   - Copy: Position the cursor, type `yy` to yank (copy) the line, or use `y` followed by a movement command.
   - Paste: Position the cursor, type `p` to paste after the cursor, or `P` to paste before the cursor.

4. **Undo and Redo:**
   - Undo: Press `u` to undo the last change.

5. **Search and Replace:**
   - Search: Press `/`, then type your search query and hit `Enter`.
   - Replace: Press `:` to enter command mode, then use `s/old/new/g` to replace all occurrences of "old" with "new".

## Advanced Techniques

Vi's power lies in mastering its commands. Here are a few advanced actions to explore:

1. **Working with Multiple Files:**
   - Open a new file when vi is already open: Press `:e filename`.

2. **Customizing Vi:**
   - Create or edit your configuration file: Open your terminal and type `vi ~/.vimrc`.

## Further Learning

Vi is a versatile tool with a wealth of features to explore. The built-in tutorial can be accessed by typing `vimtutor` in your terminal. Additionally, the Vi community is supportive, offering documentation, tutorials, and plugins. You shoud have a look on those documentations: [Basic vi Commands](https://www.cs.colostate.edu/helpdocs/vi.html) , [Vi/VIM from linuxfocus](http://linuxfocus.org/~guido/vi/), [Official docs](https://www.vim.org/docs.php)
 

Mastering Vi takes practice, but the effort is well worth it. These essential commands provide just a glimpse of Vi's capabilities. As you delve deeper into its functionalities, you'll uncover a world of text editing efficiency at your fingertips. Happy coding and writing! 😉

Desmond KPOHIZOUN
