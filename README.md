## Cousteau

Cousteau is a minimalist [Beamer][] theme with a light nautical touch. 

![cousteau title slide](http://www.mattblackwell.org/images/cousteau.png)

## Requirements

Cousteau assumes you are using [XeTeX][] to typeset you slides and that the [Fira Sans][fira] fonts (including Fira Mono) are installed on your system. 

## Installation

Copy the `.sty` files into you `texmf` tree at `$TEXMFHOME/tex/latex`. You can find where your tree is located (that is, where `$TEXMFHOME` is on your system), you can run `kpsewhich -var-value TEXMFHOME` in a terminal. 

## Usage 

For basic usage, simply put `\usetheme{cousteau}` in your preamble. 

There are a few special commands provided by the theme. In particular, `\alertb{}` and `\alertc{}` provide alternative alert colors for additional text highlighting. See `demo/cousteau-demo.tex` for more details. 

## Inspiration/Attribution

Parts of the design were inspired by the [Metropolis][] theme, with some code taken from that project. The custom alert functions inspired by the [IQSS theme][iqss]. 

## License

The theme itself is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc]. This means that if you change the theme and re-distribute it, you *must* retain the copyright notice header and license it under the same CC-BY-SA license. This does not affect the presentation that you create with the theme.


[Beamer]: https://github.com/josephwright/beamer
[fira]: https://github.com/bBoxType/FiraSans
[cc]: https://creativecommons.org/licenses/by-sa/4.0/
[XeTeX]: http://xetex.sourceforge.net/
[Metropolis]: https://github.com/matze/mtheme
[iqss]: https://github.com/IQSS/iqss-beamer-theme
