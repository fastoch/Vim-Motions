# Source Material

- https://www.youtube.com/watch?v=z4eA2eC28qg
- https://vim-adventures.com/

# Introduction

The idea is to become significantly faster by using only your keyboard.  
There's even a tool for browsing the web with only a keyboard using Vim-style keys: the **Vimium** browser extension.  

## Personal Note

For Firefox with heavy YouTube and GitHub use, **Vimium C** is usually the better fit because of its per-site mappings 
and more advanced config, which helps avoid conflicts with built-in shortcuts on those sites.  

On VSCodium, there are also multiple Vim and **Neovim** extensions.  

If you love Vim, check out the Neovim distro called **LazyVim**.  
>LazyVim From Scratch To BEAST MODE - https://www.youtube.com/watch?v=evCmP4hH7ZU

# Forget about the arrow keys

- The **h** is for moving **left**
- The **j** is for moving **down**
- The **k** key is for moving **up**
- The **l** key is for moving **right** (lower case L)

>[!tip]
>You should keep both hands on the keyboard in a position where your **index fingers** are touching the **small guides on J and F**.

# Basics

- Vim starts in **NORMAL** mode.
- To enter **INSERT** mode and start editing, you need to press the **i** key.
- To get out of insert mode and back to normal, you must press **Esc**.
- Pressing **a** is another way to drop into **insert** mode but moves your cursor one character to the right
- The **I** key enters insert mode and moves your cursor at the beginning of the line
- The **A** key enters insert mode and moves your cursor at the end of the line
- The **w** key moves your cursor to the next word
- The **b** key moves your cursor to the previous word (backward)
- The **e** key moves your cursor to the end of the current word
- The **$** key moves your cursor to the end of the line
- The **0** key moves your cursor to the beginning of the line
- The **^** key moves your cursor to the first (non-whitespace) character of the line 

# Find character

- The **f** key activates the "**find character**" mode
  - after pressing the **f** key, type the character you want to move to
  - if you want to move to the next occurrence of the character, press the **;** key
  - if you want to move to the previous occurrence of the character, press the **,** key
  - `4fs` moves to the 4th occurrence of the `s` character in the current line
  - Vim can find a character, but can also find whitespace characters

# Advanced Motions

- `3w` moves the cursor 3 words forward 
- `3b` moves the cursor 3 words backward
- To fix **indentation** (to the best of Vim's understanding), hit **=** twice
- To move to the top of a document, press `gg`
- To move to the last line of a document, press `G`
- To move to the middle of the visible screen, press `M`

# Deletion, Copying and Pasting

- To delete a word, press `dw` (it actually cuts the word)
- To delete a line, press `dd`
- To undo a deletion, press `u`
- To paste the last deleted text, press `P`

Vim copying is actually called **yanking**  
- To copy 

12/22
