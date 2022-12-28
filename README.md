# vim-cspell

vim-cspell is a plugin that checks spelling by using [cspell](https://cspell.org) for Vim/Neovim.

# Requirements

* [cspell-cli](https://cspell.org/docs/installation)
* [spelunker](https://github.com/kamykn/spelunker.vim)

# Installation

For [vim-plug](https://github.com/junegunn/vim-plug)
```vimscript

call plug#begin()
  Plug 'kamykn/spelunker.vim'
  Plug 'ryicoh/vim-cspell.vim'
call plug#end()

let g:spelunker_disable_auto_group = 1
```
