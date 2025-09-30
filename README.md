# A template for UniGraz-DH poster

This template is based on the `beamerposter` class written by Philippe Dreuw and Thomas Deselaers.

## Philosophy

The class is a derivate of the well-known `beamer` class for presentation slides.
+ The layout is a hierarchy of `block` and `column` elements. Blocks are stacked upon each other; columns line up from left to right.  A column may contain other columns or a stack of blocks.
+ Two stylesheets (a beamerposter stylesheet and a color theme) are needed: they can be customized, but it requires more effort than one would like when working under a deadline. Hence this attempt at prototyping a UniGraz theme.


## How to use

In the Linux shell

1. Verify that
   + the `beamer` package is part of your LaTeX setup
   + you use the **`lualatex`** engine (not `pdflatex`)
   + the beamer Gemini `*.sty` theme files provided here are in your work directory
2. Run:

```
$ lualatex poster
```

Overleaf:

1. Download this repo as a ZIP file
2. Upload to your Overleaf project


![Poster example](poster_example.png)


The beamer package can be found at:
![https://github.com/deselaers/latex-beamerposter](https://github.com/deselaers/latex-beamerposter)

The Gemini theme used for this template:
![https://github.com/anishathalye/gemini/blob/master/poster.tex](https://github.com/anishathalye/gemini/blob/master/poster.tex)

