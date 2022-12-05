# University of Oregon Beamer Theme

## Description
- Unofficial UO beamer theme
- This work is almost entirely based on [a custom Beamer theme for Oregon State University](https://github.com/jeremy-lilly/osu-beamer-theme) by Jeremy Lilly and Michael Kupperman, with changes for University of Oregon design guides.

## Usage
- Place all `*.sty` files and your `*.tex` files in the same directory and run `lualatex` or `xelatex`. I use [TeXLive 2022](https://www.tug.org/texlive/), [Visual Studio Code](https://code.visualstudio.com/), and [LaTeX Workshop Extension for Visual Studio Code](https://github.com/James-Yu/LaTeX-Workshop).
- You can import theme elements in part with [Beamer themes](https://deic.uab.cat/~iblanes/beamer_gallery/) as below:
```{latex}
% truncated ...
% Selects the Warsaw theme
\usetheme{Warsaw}
% Use UO color and font themes
\usecolortheme{UO}
\usefonttheme{UO}
% truncated ...
```
- For macros defined in the original works, please refer to the page of [the original work](https://github.com/jeremy-lilly/osu-beamer-theme)
- Users will need to install LaTeX packages `sourcesanspro`, `sourceserifpro`, `fontspec`, `fontenc`, and others before use.

## Acknowledgments
- I really appreciate the original works of Jeremy Lilly and Michael Kupperman.

## Reference
- University Communications, University of Oregon
    - [Typography](https://communications.uoregon.edu/brand/typography)
    - [Color](https://communications.uoregon.edu/brand/color)
    - [Logos and Marks](https://communications.uoregon.edu/brand/logos-and-marks)