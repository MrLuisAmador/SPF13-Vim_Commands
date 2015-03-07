#Spf13-Vim Keyboard Commands/Shortcuts

This is my public reference of the keyboard commands/shortcuts that will help you quickly be productive with [spf13-vim](https://github.com/spf13/spf13-vim).
This is for people wanting to make the switch from **Sublime Text** to **Vim**. My goal is to be able to reference all of the popular 
shortcuts that we use with Sublime Text and display how to do them with spf13-vim.

FYI, All of this information can be attained by searching for the **README** file of each installed plugin of spf13-vim. You will
also have to be familiar with using **Vim**, so come back once you feel comfortable with Vim and your wrist will thank you in the future.

##Vim Command Mode

I consider this the command palette of **Vim**. There is too much to document on the command mode, so once again, I’m only going to display what I feel is in comparison to 
Sublime Text.

##General 

| Source          | Command            | Mac OS X | Windows/Linux     | Description |
| ---------       | --------           | -------  | -----             |----------   |
| Basic Vim       | Command Mode       |          | `shift + :`       |             |
| Basic Vim       | Help documentation |          | `:h {query}`      |             |


##File

    | Source            | Command                 | Mac OS X | Windows/Linux               | Description |
    | ---------         | --------                | -------  | -----                       | ----------  |
    | Basic Vim         | New file/buffer         |          | `:e {New filename}`         |             |
    | Basic Vim         | Open a files/buffers    |          | `:e {/dir/{filename}`       |             |
    | Basic Vim         | Open recent file/buffer |          |                             |             |
    |                   |                         |          |                             |             |
    | Basci Vim         | List open files/buffers |          | `:ls`                       |             |
    | Basci Vim         | Go to next files/buffers|          | `:bn {number or filename}`  |             |
    | Basci Vim         | Close files/buffers     |          | `:bd {numbers or filenames}`|             |
    |                   |                         |          |                       |             |
    | Basic Vim         | Save                    |          | `:w`                  |             |
    | Basic Vim         | Save-as                 |          | `:sav {filename}`     |             |
    | Basic Vim         | Save-all                |          | `:wa`                 |             |
    |                   |                         |          |                       |             |
    | Basic Vim         | Quit                    |          | `:q`                  |             |
    | Basic Vim         | Quit-all                |          | `:qa`                 |             |
    | Basic Vim         | Save and quit-all       |          | `:wqa`                |             |


##Edit

    |                   |                         |          |                       |             |
    | Basic Vim         | Undo                    |          | `u`                   |             |
    | Basic Vim         | Redo                    |          | `:redo`               |             |
    |                   |                         |          |                       |             |
    | Basic Vim         | Copy/Yank line          |          | `yy`                  |             |
    | Basic Vim         | Cut line                |          | `dd`                  |             |
    | Basic Vim         | Copy/Yank selection or copy charater under cursor |          | `y`                   |             |
    | Basic Vim         | Cut selection           |          | `d`                   |             |
    | Basic Vim         | Cut charater under cursor |          | `x`                   |             |
    |                   |                         |          |                       |             |
    | Basic Vim         | Paste after the cursor  |          | `p`                   |             |
    | Basic Vim         | Paste before the cursor |          | `p`                   |             |
    |                   |                         |          |                       |             |
    | Basic Vim         | Show Clipboard/Resigters|          | `:di`                 |             |
    | Basic Vim         | Copy to Clipboard/Resigters|       | `”{letter}y`          |             |
    | Basic Vim         | Paste Clipboard/Resigters|       | `”{letter}p`          |             |
    |                   |                         |          |                       |             |
    | Default spf13-vim | move to right tab       |          | `shift + l`           |             |
    | Basic Vim         | Horizontal split        |          | `:sp`                 |             |
    | Basic Vim         | Vertical split          |          | `:vs`                 |             |
    | Default spf13-vim | move to left buffer     |          | `ctrl + h`            |             |
    | Default spf13-vim | move to right buffer    |          | `ctrl+ l`             |             |
    | Default spf13-vim | move to top buffer      |          | `shift + k`           |             |
    | Default spf13-vim | move to bottom buffer   |          | `shift + j`           |             |
    |                   |                         |          |                       |             |
    |                   |                         |          |                       |             |
    |                   |                         |          |                       |             |
    | Basic Vim         | increment up a number   |          | `ctrl + a`            |             |
    | Basic Vim         | increment down a number |          | `ctrl + x`            |             |

##Name Here


    |                   |                         |          |                       |             |
    | Basic Vim         | New tab                 |          | `:tabe`               |             |
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
    |                   |                         |          |                       |             |
    |                   |                         |          |                       |             |
    | Basic Vim         | increment up a number   |          | `ctrl + a`            |             |
    | Basic Vim         | increment down a number |          | `ctrl + x`            |             |

##Plug-ins

| Source                                                    | Command                              | Mac OS X | Windows/Linux     | Description |
| ---------                                                 | --------                             | -------  | -----             |----------   |
| [vim-commentary](https://github.com/tpope/vim-commentary) | Comment or uncomment a line of code  |          | `gcc`             |             |
| [vim-commentary](https://github.com/tpope/vim-commentary) | Comment or uncomment a block of code |          | `gc`              |             |
|                                                           |                                      |          |                   |             |



-------------------------------------------------------------------------
Added by me to my vimrc.local -- Move a line or block of code up or down:

````
block or line up = shift + k

````
block or line down = shift + j



