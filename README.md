# vim-colors
White style theme For vim

create by [Lan](mailto:bluescode@outlook.com) base on [molokai](https://github.com/tomasr/molokai)
date: 2017-03-29

### How to use ?

1. download **/colors/*.vim** file to your computer
2. move colors file to path: `~/.vim/colors/*.vim` 
3. modify `~/.vimrc` like this:

```
  syntax enable
  syntax on
  " display number
  set nu
  " display cursor position
  set ruler
  " highlight current line
  set cursorline
  " when a file is not save or read-only, a confirmation dialog pops up
  set confirm
  " enable file type detection
  filetype on
  " according to file type load different plug-in
  filetype plugin on
  " set background theme
  set background=light
  " the name of your theme file in `~/.vim/colors/`, do not contain suffix
  colorscheme Lan
```
4. enjoy it
