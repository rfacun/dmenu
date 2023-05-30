# rfacun's `dmenu`
This custom build of `dmenu` is part of [my dotfiles](https://github.com/rfacun/dotfiles).

## Patches applied
- [x] [fuzzyhighlight](https://tools.suckless.org/dmenu/patches/fuzzyhighlight/):
fuzzy matches gets highlighted.
- [x] [fuzzymatch](https://tools.suckless.org/dmenu/patches/fuzzymatch/):
adds support for fuzzy-matching to `dmenu`, allowing users to type
non-consecutive portions of the string to be matched.

## Install
```
git clone https://github.com/rfacun/dmenu.git
cd dwm
sudo make clean install
```
