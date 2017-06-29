# VIM Cheat Sheet Keyboard Commands/Shortcuts

This is my public reference of the keyboard commands/shortcuts that will help you quickly be productive with VIM.

This is for people wanting to make the switch from **nano** to **Vim**. My goal is to be able to reference all of the popular commands and shortcuts that we use with VIM.

##General

| Source          | Command            | Mac OS X | Windows/Linux     | Description |
| ---------       | --------           | -------  | --------------    |----------   |
| Basic Vim       | Command Mode       |          | `shift + :`       |             |
| Basic Vim       | Help documentation |          | `:h {query}`      |             |
| Basic Vim       | Your config file   |          | `:e $MYVIMRC`     |             |

##File

| Source            | Command                 | Mac OS X | Windows/Linux               | Description |
| ---------         | ----------------------  | -------  | ----------------            | ----------  |
| Basic Vim         | New file/buffer         |          | `:e {New filename}`         |             |
| Basic Vim         | Open file in new tab    |          | `:tabe {New filename}`      |             |
|                   |                         |          |                             |             |
| Basci Vim         | List open files/buffers |          | `:ls`                       |             |
| Basci Vim         | Go to next files/buffers|          | `:bn {number or filename}`  |             |
| Basci Vim         | Close files/buffers     |          | `:bd {numbers or filenames}`|             |
|                   |                         |          |                             |             |
| Basic Vim         | Save                    |          | `:w`                        |             |
| Basic Vim         | Save-as                 |          | `:sav {filename}`           |             |
| Basic Vim         | Save-all                |          | `:wa`                       |             |
|                   |                         |          |                             |             |
| Basic Vim         | Quit                    |          | `:q`                        |             |
| Basic Vim         | Quit-all                |          | `:qa`                       |             |
| Basic Vim         | Save and quit-all       |          | `:wqa`                      |             |

##Edit

| Source            | Command                                           | Mac OS X                 | Windows/Linux         | Description |
| ---------         | ----------------------                            | -------                  | ----------------      | ----------  |
|                   |                                                   |                          |                       |             |
| Basic Vim         | Undo                                              |                          | `u`                   |             |
| Basic Vim         | Redo                                              |                          | `Ctrl + r`            |             |
|                   |                                                   |                          |                       |             |
| Basic Vim         | Copy/Yank line                                    |                          | `yy`                  |             |
| Basic Vim         | Cut line                                          |                          | `dd`                  |             |
| Basic Vim         | Copy/Yank selection or copy charater under cursor |                          | `y`                   |             |
| Basic Vim         | Cut selection                                     |                          | `d`                   |             |
| Basic Vim         | Cut charater under cursor                         |                          | `x`                   |             |
|                   |                                                   |                          |                       |             |
| Basic Vim         | Paste after the cursor                            |                          | `p`                   |             |
| Basic Vim         | Paste before the cursor                           |                          | `p`                   |             |
|                   |                                                   |                          |                       |             |
| Basic Vim         | Show Clipboard/Resigters                          |                          | `:di`                 |             |
| Basic Vim         | Copy to Clipboard/Resigters                       |                          | `”{letter}y`          |             |
| Basic Vim         | Paste Clipboard/Resigters                         |                          | `”{letter}p`          |             |
|                   |                                                   |                          |                       |             |
| Default spf13-vim | move to right tab                                 |                          | `shift + l`           |             |
| Basic Vim         | Horizontal split                                  |                          | `:sp`                 |             |
| Basic Vim         | Vertical split                                    |                          | `:vs`                 |             |
| Default spf13-vim | move to left buffer                               |                          | `ctrl + h`            |             |
| Default spf13-vim | move to right buffer                              |                          | `ctrl+ l`             |             |
| Default spf13-vim | move to top buffer                                |                          | `shift + k`           |             |
| Default spf13-vim | move to bottom buffer                             |                          | `shift + j`           |             |
|                   |                                                   |                          |                       |             |
|                   |                                                   |                          |                       |             |
|                   |                                                   |                          |                       |             |
| Basic Vim         | increment up a number                             |                          | `ctrl + a`            |             |
| Basic Vim         | increment down a number                           |                          | `ctrl + x`            |             |

## View

| Source            | Command                 | Mac OS X | Windows/Linux         | Description |
| ---------         | ----------------------  | -------  | ----------------      | ----------  |
|                   |                         |          |                       |             |
| Default spf13-vim | move to left tab        |          | `shift + h`           |             |
| Default spf13-vim | move to right tab       |          | `shift + l`           |             |
|                   |                         |          |                       |             |
| Basic Vim         | Horizontal split        |          | `:sp`                 |             |
| Basic Vim         | Vertical split          |          | `:vs`                 |             |
| Default spf13-vim | move to left buffer     |          | `ctrl + h`            |             |
| Default spf13-vim | move to right buffer    |          | `ctrl+ l`             |             |
| Default spf13-vim | move to top buffer      |          | `shift + k`           |             |
| Default spf13-vim | move to bottom buffer   |          | `shift + j`           |             |
|                   |                         |          |                       |             |
| Basic Vim         | increment up a number   |          | `ctrl + a`            |             |
| Basic Vim         | increment down a number |          | `ctrl + x`            |             |

##Plug-ins

| Source                                                    | Command                              | Mac OS X | Windows/Linux     | Description |
| ---------                                                 | --------                             | -------  | -----             |----------   |
| [ctrlp.vim](https://github.com/kien/ctrlp.vim)            | Open up fuzzy search                 |          | `ctrl + p`        |             |
|                                                           | Open the file in V split             |          | `ctrl + v`        |             |
|                                                           | Open the file in new tab             |          | `ctrl + t`        |             |
|                                                           |                                      |          |                   |             |
| [vim-commentary](https://github.com/tpope/vim-commentary) | Comment or uncomment a line of code  |          | `gcc`             |             |
|                                                           | Comment or uncomment a block of code |          | `gc`              |             |
|                                                           |                                      |          |                   |             |
| [emmet-vim](http://mattn.github.com/emmet-vim)            | Expand emmet syntax                  |          | `ctrl + y ,`      |             |



-------------------------------------------------------------------------
Added by me to my vimrc.local -- Move a line or block of code up or down:

````
block or line up = shift + k

````
block or line down = shift + j
