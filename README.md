# ds2rse
Holds the paper project for INFORMATIK 2025 for comparative analysis of DS competencies and RSE competencies

The precompiled current document can be found [here](https://github.com/the-teachingRSE-project/ds2rse/blob/build/index.pdf)

## HOW TO CONTRIBUTE

- edit index.qmd following quarto markdown rules
- in the add further bib-files
- in authors.tex you can add yourself
- NOTE: if you have problems with the quarto pipeline, just add the content to index.qmd file and I will check this out

## HOW to run

- install quarto with tinytex extension
- **alternatively, if you already have TeX Live on your system** you don't need
  tinytex: Just install the missing packages of your TeX Live installation.
  You'll need the LaTeX class [`lni` (Lecture Notes in
  Informatics)](https://www.ctan.org/pkg/lni). For Debian/Ubuntu based systems
  this is included in the package [`texlive-publishers`](https://packages.debian.org/trixie/texlive-publishers).
- run quarto render index.qmd --to pdf (should produce a pdf in LNI format)
- debug problems in generated index.tex file
- have a look at syntax_example.qmd for the most important quarto stuff


## Content TODOs

see issue 9

## Technical TODOs

- add deRSE bibliography as submodule
- check that the LNI-template complies to the LNI-format and generates the correct latex
    - have a look at https://quarto.org/docs/journals/templates.html
    - and LNI overleaf examples
- investigate edge cases of quarto features and how they are translated to latex

## Known Problems

- I had to install ngerman manually with tinytex (first finding out where quarto put the tinytex executables)
