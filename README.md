# base16-dynamic colorscheme for Vim

## Original
[base16-vim](https://github.com/chriskempson/base16-vim)
by [Chris Kempson](http://chriskempson.com)

## Usage
1. if you want to disable italic font (enabled by default):

```vim
let g:base16#enable_italics = 0
```

2. set base16 pallet (base00 to base0F):

example from: <https://github.com/ntpeters/base16-materialtheme-scheme/blob/master/material.yaml>

```vim
let g:base16#pallet = {"base00": "263238", "base01": "2E3C43", "base02": "314549", "base03": "546E7A", "base04": "B2CCD6", "base05": "EEFFFF", "base06": "EEFFFF", "base07": "FFFFFF", "base08": "F07178", "base09": "F78C6C", "base0A": "FFCB6B", "base0B": "C3E88D", "base0C": "89DDFF", "base0D": "82AAFF", "base0E": "C792EA", "base0F": "FF5370"}
```

3. after setting these variables:

```vim
colorscheme base16-dynamic
```

## License
original software ([chriskempson/base16-vim](https://github.com/chriskempson/base16-vim)):
[MIT](https://github.com/chriskempson/base16-vim/blob/master/LICENSE.md)
