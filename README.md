# Vim To Do
Simple syntax highlighting for vim todo notes.

# Usage:
- download notes.vim file & put in ~/.vim/colors/ (or wherever your vim config files are located)
- use colorscheme in vim with `:color notes`
- or put this in .vimrc so any *.n file will use this colorscheme
```
syntax highlighting for notes
autocmd BufWinEnter *.n colorscheme notes
autocmd BufWinEnter *.n set nonumber
autocmd BufWinEnter *.n set foldcolumn=2
```
