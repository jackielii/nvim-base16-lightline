# nvim-base16-lightline

Uses [nvim-base16](https://github.com/RRethy/nvim-base16) for [vim-lightline](https://github.com/itchyny/lightline.vim)

## Install

```
Plug 'jackielii/nvim-base16-lightline'
```

## Config

```VimL
let g:lightline = {
\   'colorscheme': 'base16'
\ }

" automatically update lightline when colroschem changes
au ColorScheme * call UpdateLightlineBase16()
```
