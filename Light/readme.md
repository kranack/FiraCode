
## Which font?

### TL;DR

0. Pick your font family and then select from the `'complete'` directory.
  * Are you on Windows? Pick a font with the suffix `'Windows Compatible'`
  * Are you limited to mono fonts (because of your terminal, etc)? Pick a font with the suffix `'Mono'`

### Explanation

Once you narrow done your font choice of family (`Droid Sans`, `Inconsolata`, etc) and style (`bold`, `italic`, etc) you have 2 main choices:
 * download an already patched font from the `complete` folder
  * This is most likely the one you want. It includes **all** of the glyphs from all of the glyph sets. Only caution here is that some fonts have glyphs in the _same_ code point so to include everything some had to be moved to alternate code points.
 * patch your own variations with the various options provided by the font patcher (see each font's readme for full list of combinations available)
  * This contains a list of _all permutations_ of the various glyphs. E.g. You want the font with only [Octicons][octicons] or you want the font with just [Font Awesome][font-awesome] and [Devicons][vorillaz-devicons]. The goal is to provide every combination possible in this folder.


For more information see: [The FAQ](https://github.com/ryanoasis/nerd-fonts/wiki/FAQ#which-font)


[vim-devicons]:https://github.com/ryanoasis/vim-devicons
[vorillaz-devicons]:http://vorillaz.github.io/devicons/
[font-awesome]:https://github.com/FortAwesome/Font-Awesome
[octicons]:https://github.com/github/octicons
[gabrielelana-pomicons]:https://github.com/gabrielelana/pomicons
[Seti-UI]:https://atom.io/themes/seti-ui
[ryanoasis-powerline-extra-symbols]:https://github.com/ryanoasis/powerline-extra-symbols

## Variations (Combinations)

> The combinations and total number of combinations are provided here for reference if you want to create your own variation of a patched Nerd Font.

### Why aren't all variations included ?

Combinations are no longer included by default because of the large inflation in size it caused the Repository _and_ the amount of time it takes to rebuild all of the combinations. This issue would exponentially get worse as the numbers of Fonts and Glyph Sets provided increase.


```sh
# 510 Possible Combinations:

./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontlinux
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --octicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontlinux
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesome
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontlinux
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --octicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontlinux
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --windows
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontlinux
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --octicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontlinux
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesome
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontlinux
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --octicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontlinux
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --pomicons
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --powerlineextra
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --fontawesomeextension
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs --powersymbols
./font-patcher FiraCode-Light.otf  --use-single-width-glyphs
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontlinux
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --pomicons
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --octicons
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontlinux
./font-patcher FiraCode-Light.otf  --windows --fontawesome --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontawesome --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --pomicons
./font-patcher FiraCode-Light.otf  --windows --fontawesome --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontawesome --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesome
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --fontlinux
./font-patcher FiraCode-Light.otf  --windows --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --octicons --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --octicons --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --pomicons
./font-patcher FiraCode-Light.otf  --windows --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --octicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --octicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --octicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --octicons
./font-patcher FiraCode-Light.otf  --windows --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --windows --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontlinux
./font-patcher FiraCode-Light.otf  --windows --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --windows --pomicons
./font-patcher FiraCode-Light.otf  --windows --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --windows --powerlineextra
./font-patcher FiraCode-Light.otf  --windows --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --windows --fontawesomeextension
./font-patcher FiraCode-Light.otf  --windows --powersymbols
./font-patcher FiraCode-Light.otf  --windows
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontlinux
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --pomicons
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --powerlineextra
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --octicons --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --octicons
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --fontlinux
./font-patcher FiraCode-Light.otf  --fontawesome --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --fontawesome --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --pomicons
./font-patcher FiraCode-Light.otf  --fontawesome --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --powerlineextra
./font-patcher FiraCode-Light.otf  --fontawesome --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontawesome --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesome
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --octicons --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --fontlinux
./font-patcher FiraCode-Light.otf  --octicons --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --octicons --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --octicons --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --octicons --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --pomicons
./font-patcher FiraCode-Light.otf  --octicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --octicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --powerlineextra
./font-patcher FiraCode-Light.otf  --octicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --octicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --octicons --powersymbols
./font-patcher FiraCode-Light.otf  --octicons
./font-patcher FiraCode-Light.otf  --fontlinux --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontlinux --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontlinux --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontlinux --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --fontlinux --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontlinux --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontlinux --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --fontlinux --pomicons
./font-patcher FiraCode-Light.otf  --fontlinux --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontlinux --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontlinux --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --fontlinux --powerlineextra
./font-patcher FiraCode-Light.otf  --fontlinux --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontlinux --fontawesomeextension
./font-patcher FiraCode-Light.otf  --fontlinux --powersymbols
./font-patcher FiraCode-Light.otf  --fontlinux
./font-patcher FiraCode-Light.otf  --pomicons --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --pomicons --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --pomicons --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --pomicons --powerlineextra
./font-patcher FiraCode-Light.otf  --pomicons --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --pomicons --fontawesomeextension
./font-patcher FiraCode-Light.otf  --pomicons --powersymbols
./font-patcher FiraCode-Light.otf  --pomicons
./font-patcher FiraCode-Light.otf  --powerlineextra --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --powerlineextra --fontawesomeextension
./font-patcher FiraCode-Light.otf  --powerlineextra --powersymbols
./font-patcher FiraCode-Light.otf  --powerlineextra
./font-patcher FiraCode-Light.otf  --fontawesomeextension --powersymbols
./font-patcher FiraCode-Light.otf  --fontawesomeextension
./font-patcher FiraCode-Light.otf  --powersymbols
```