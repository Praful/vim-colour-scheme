This repository contains files that affect how GVim appears. I created these a few years ago when I started using Vim. I've never got round to refining them, probably because they've served their purpose.

# deep-onyx.vim

Here's a screenshot of a Ruby file using this theme:

![deep-onyx theme](gvim1.jpg)

The font used in the screenshot is [DejaVu Sans Mono for Powerline](https://github.com/powerline/fonts/tree/master/DejaVuSansMono). The Powerline font is used for enhancing the status line with vim-airline. The non-Powerline DejaVu Sans Mono font is available [here](https://dejavu-fonts.github.io/).

This Vim theme is intended to be used in GVim. It may be fine in a terminal with true colour support, such as [ConEmu](https://conemu.github.io/).

To use the theme:

1. Copy `deep-onyx.vim` to `~/.vim/colors` (Linux) or `%USERPROFILE%/vimfiles/colors` (Windows).
2. Add `colorscheme deep-onyx` to your `vimrc` file (generic Vim setup) or `.vimrc` (Linux) or `_vimrc` (Windows).

# bubblegum2.vim

This is a [vim-airline](https://github.com/vim-airline/vim-airline) theme. Here's a screenshot of the airline status line in normal mode using this theme:


![bubblegum2 airline theme](gvim2.jpg)

To use the theme:

1. Copy `bubblegum2.vim` to `~/.vim/autoload/airline/themes` (Linux) or `%USERPROFILE%/vimfiles/autoload/airline/themes` (Windows).
2. Add `let g:airline_theme='bubblegum2'` to your `vimrc` file (generic Vim setup) or `.vimrc` (Linux) or `_vimrc` (Windows).
