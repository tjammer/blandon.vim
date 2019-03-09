A light color scheme for Vim/Neovim based on a color palette created by [Landon Schropp][landonLink], which I found in his [dotfiles][dotfilesLink]. The colorschemes for vim and vim-airline were created using the [base16-builder][base16Link], then adapted slightly to my needs.

![blandon][screenshot]

## Usage
Install the color scheme with your favorite plugin manager and activate it by:
```vim
colorscheme blandon
```

## Lightline
This color scheme also includes an airline color scheme, which can be used by adding the following line to the .vimrc:
```vim
let g:airline_theme = "blandon"
```

[screenshot]: screenshot.png
[landonLink]: https://github.com/LandonSchropp
[dotfilesLink]: https://github.com/LandonSchropp/dotfiles
[base16Link]: https://github.com/base16-builder/base16-builder
