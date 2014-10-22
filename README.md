initial commit# What is this

This is a repository that contains my up-to-date CV in LaTeX which is based on the acadameic research CV template.

The academic research CV template integrates the following packages:

* biblatex (with modifications)
* moderncv
* moderntimeline
* pdfpages
* xpatch

# How to build

pdflatex main.tex <br />
biber main.bcf <br />
pdflatex main.tex <br />
pdflatex main.tex <br />

# HTML Version

The pdf can be compiled into an HTML version, using [pdf2htmlex](https://github.com/coolwanglu/pdf2htmlEX). Once you have 'pdf2htmlex' installed you can convert the pdf to html using the following command:

pdf2htmlex main.pdf
