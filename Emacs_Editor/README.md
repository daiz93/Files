# Mastering Emacs: A Short Guide to Common Commands

[Emacs](https://en.wikipedia.org/wiki/GNU_Emacs), a powerful and extensible text editor, has been an attractive editor for coding and text manipulation for decades. Its flexibility and wide range of features make it the tool of choice for programmers. It is free under the [GPLv3 licence](https://www.gnu.org/licenses/gpl-3.0.html) and available for Windows, Linux and Mac OS. 😊 Its graphical version lets you use the mouse even if you have most of the commands on the keyboard. 🖱️ I was lucky enough to discover it on the command line during my time as a software engineer. In this little guide, I'll explore a few common Emacs commands that I'm sure will help you get to grips with this code editor 😉

## Installation and Basic Usage

Before diving into commands, ensure you have Emacs installed. You can download it from the official website or use your system's package manager. Once installed, launch Emacs from the command line with the `emacs` command. Here's how to get started:

1. **Opening and Creating Files:**
   - To open a file: Press `Ctrl` + `X`, `Ctrl` + `F` and then provide the path to the file. If the file does not exist, it will creat it as a new file.
   - To create a new file: Press `Ctrl` + `X`, `Ctrl` + `F` and enter a new filename.

2. **Basic Navigation:**
   - Move the cursor: Use arrow keys or `Ctrl` + `P` (previous line), `Ctrl` + `N` (next line), `Ctrl` + `B` (backward), and `Ctrl` + `F` (forward).

3. **Saving and Quitting:**
   - Save: Press `Ctrl` + `X`, `Ctrl` + `S`.
   - Save and Quit: Press `Ctrl` + `X`, `Ctrl` + `S`, then `Ctrl` + `X`, `Ctrl` + `C`.

## Efficient Editing

Emacs' true power shines through when it comes to efficient text manipulation. Here are some commands to enhance your editing experience:

1. **Cut, Copy, Paste:**
   - Cut: Mark the text with `Ctrl` + `Space`, move the cursor, then `Ctrl` + `W` or `Ctrl` + `K`.
   - Copy: Mark the text with `Ctrl` + `Space`, move the cursor, then `Meta` + `W`.
   - Paste: `Ctrl` + `Y`.

2. **Undo and Redo:**
   - Undo: `Ctrl` + `_` or `Ctrl` + `X`, `Ctrl` + `U`.
   - Redo: `Ctrl` + `Shift` + `_`.

3. **Search and Replace:**
   - Search: `Ctrl` + `S`, then type your search query and press `Enter`.
   - Replace: `Alt` + `Shift` + `5`, then enter the text to find and its replacement.

## Advanced Functions

Emacs' extensibility lies in its ability to run scripts and plugins, known as "modes." Here are some advanced commands:

1. **Working with Buffers:**
   - Create a new buffer: `Ctrl` + `X`, `b`.
   - Switch between buffers: `Ctrl` + `X`, `b`, then select the buffer from the list.

2. **Using Modes:**
   - Activate a mode: `Alt` + `X`, then type the mode name (e.g., `python-mode`, `markdown-mode`).

3. **Customization:**
   - Edit Emacs configuration: `Ctrl` + `X`, `Ctrl` + `F`, then enter `~/.emacs` to create or edit your configuration file.

## Learning More

Emacs is a vast and intricate tool with much more to explore. The built-in tutorial can be accessed by typing `Ctrl` + `H`, `T`. Additionally, the Emacs community is active and supportive, offering tutorials, documentation, and extensions. Have a look on the [oficial documentation of Emacs](https://www.gnu.org/software/emacs/documentation.html)

Mastering Emacs takes time, but with practice, you can harness its immense capabilities. These common commands are just the tip of the iceberg, and by delving into its features, you'll find a world of text editing efficiency at your fingertips. Happy coding and writing! 😉

Desmond KPOHIZOUN 

