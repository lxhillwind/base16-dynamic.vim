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

example from:

<https://github.com/ntpeters/base16-materialtheme-scheme/blob/master/material.yaml>
<https://github.com/purpleKarrot/base16-one-light-scheme/blob/master/one-light.yaml>

```vim
" present
let g:base16#pallet#dark = {"base00": "263238", "base01": "2E3C43", "base02": "314549", "base03": "546E7A", "base04": "B2CCD6", "base05": "EEFFFF", "base06": "EEFFFF", "base07": "FFFFFF", "base08": "F07178", "base09": "F78C6C", "base0A": "FFCB6B", "base0B": "C3E88D", "base0C": "89DDFF", "base0D": "82AAFF", "base0E": "C792EA", "base0F": "FF5370"}
let g:base16#pallet#light = {"base00": "fafafa", "base01": "f0f0f1", "base02": "e5e5e6", "base03": "a0a1a7", "base04": "696c77", "base05": "383a42", "base06": "202227", "base07": "090a0b", "base08": "ca1243", "base09": "d75f00", "base0A": "c18401", "base0B": "50a14f", "base0C": "0184bc", "base0D": "4078f2", "base0E": "a626a4", "base0F": "986801"}
```

These settings are both optional.

3. after setting these variables:

```vim
colorscheme base16-dynamic
```

Run `set bg=dark` / `set bg=light` to toggle theme.

## License
original software ([chriskempson/base16-vim](https://github.com/chriskempson/base16-vim)):
[MIT](https://github.com/chriskempson/base16-vim/blob/master/LICENSE.md)


## Credit
present pallet:

- Material: Nate Peterson <https://github.com/ntpeters/base16-materialtheme-scheme>
- One Light: Daniel Pfeifer <https://github.com/purpleKarrot/base16-one-light-scheme>
