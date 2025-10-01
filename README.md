# A template for UniGraz-DH posters

This template is based on the `beamerposter` class written by Philippe Dreuw and Thomas Deselaers, as well as on a slightly modified version of the `Gemini` Beamer theme.


## Philosophy

The class is a derivate of the well-known `beamer` class for presentation slides.
+ The layout is a hierarchy of `block` and `column` elements. Blocks are stacked upon each other; columns line up from left to right.  A column may contain other columns or a stack of blocks.
+ Two stylesheets are needed: a beamerposter stylesheet and a color theme. The latter is easy to adapt to your needs; the former is harder if you are not a bit acquainted with the Beamer package syntax.
+ Existing Beamer styles usually emphasize simplicity and ease of reading anyway
+ If you already use Beamer for your presentations, recycling slides into a Beamer poster is straightforward.

 $\to$ better choose Beamer if you already use and like Beamer for slides and are happy with the provided stylesheets.


## How to use

In the Linux shell

1. Verify that
   + The `beamer` package is part of your LaTeX setup.
   + You use the **`lualatex`** engine (not `pdflatex`).
   + The beamer Gemini `*.sty` theme files provided here are in your work directory
2. Run:

```
$ lualatex poster
```

Overleaf:

1. Download this repo as a ZIP file
2. Upload to your Overleaf project


![Poster example](poster_example.png)


The source for BeamerPoster can be found at:
![https://github.com/deselaers/latex-beamerposter](https://github.com/deselaers/latex-beamerposter)

The `beamerposter` LaTeX package at CTAN:
![https://ctan.org/pkg/beamerposter](https://ctan.org/pkg/beamerposter)

The Grazmini theme provided here is a modified version of the (MIT-flavored) Gemini theme:
![https://github.com/anishathalye/gemini/blob/master/poster.tex](https://github.com/anishathalye/gemini/blob/master/poster.tex)

