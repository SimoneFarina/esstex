ESS LaTeX Styles for Presentation and Document
=================

# Why another ESS latex styles

* I've developed the beamer and document style files in order to create my own presentation and document by using a typical latex instead of pdflatex. And I have my own long-lasting style file for them. There are some TeX style files, please see the below links) at ESS, but I prefer to use a legacy method (latex, xdvi, emacs, dvips, dvipdf, and so on)

 * https://bitbucket.org/europeanspallationsource/ess-latex
 * https://bitbucket.org/europeanspallationsource/ess-latex-templates

# Usage

* Generic commands

```
$ latex a.tex
$ latex a.tex
$ bibtex a.aux
$ latex a.tex
$ dvipdf a.dvi
```

# Makefile for them

* There is a good Makefile for LaTeX, one should check the following site:
 * https://github.com/shiblon/latex-makefile
* Makefile.ini replaces the default command from pdflatex, which is used in Makefile, to latex. 


# Contact

* (Jeong) Han Lee
* jeonghan.lee@gmail.com
* han.lee@esss.se




