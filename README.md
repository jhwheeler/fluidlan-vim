fluidlan-vim
==============

fluidlan vim colorscheme is a modified version of [space-vim-dark](https://github.com/liuchengxu/space-vim-dark), which is in turn derived from [spacemacs-dark-theme](https://github.com/nashamri/spacemacs-theme). The main differentiator from spacemacs-vim-dark is the lack of orange, except for TODOs and FIXMEs. This theme is somewhat closer to the original spacemacs dark theme.

![Fluidlan Vim Color Theme](https://user-images.githubusercontent.com/23257850/88414702-db760e80-ce0f-11ea-9ae4-29f221612e77.png)

## Installation

Follow your favourite plugin manager's instruction, e.g., [vim-plug](https://github.com/junegunn/vim-plug):

```vim
Plug 'jhwheeler/fluidlan-vim'
```

## GUI or Terminal with true colors enabled

```vim
color fluidlan
set termguicolors
hi Normal     ctermbg=NONE guibg=NONE
hi LineNr     ctermbg=NONE guibg=NONE
hi SignColumn ctermbg=NONE guibg=NONE
```
