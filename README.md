## University of New South Wales Beamer Theme

A Latex beamer theme for [University of New South Wales](https://www.unsw.edu.au/).
Design was based on the [Saarland beamer template](https://github.com/kailashbuki/beamerthemesaarland) and the guidelines listed in the [UNSW Visual Guide](https://www.brand.unsw.edu.au/download/).

## Tutorial and some comments

* Follow [`slides.tex`](slides.tex) to make your own slides. 
  * Personally, I used Tex Studio in compiling this Latex Beamer code.
  * Check out [`slides.pdf`](slides.pdf) for a sample output.
* If you want to use Beamer with presenter view (like Microsoft PPT), check out [Dual Screen PDF viewer for latex beamer](https://github.com/dannyedel/dspdfviewer) and its [installation procedure](http://dspdfviewer.danny-edel.de/#how-do-i-install-it). You'll also have to generate the slides.pdf with notes [something like this](slides-with-notes.pdf)
  * Make you uncomment the following code snippets at `slides.tex`
```
%\usepackage{pgfpages}
%\setbeameroption{show notes on second screen}
```
* For more advance slideshow techniques, check out `advance\main.tex` and `advance\main.pdf` for a more complicated example. This code made my APR slides during my 1st year of PhD. I won't be including the figures though so you won't be able to rebuild it.