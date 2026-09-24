DATA301/DATA471 Assignment 4
============================

AUTHOR
------

  Leon Cai (300692424)

FILES
-----

  assignment4.qmd    : Quarto source (both exercises)
  references.bib     : bibliography for the sources cited in the report
  assignment4.pdf     : rendered report

CONTENTS
--------

  Exercise 1 : comparing the ML and IQR-based estimators of the rate of an
               Exponential distribution, a bootstrap bias-corrected
               estimator, and a Monte Carlo comparison of the three by
               mean squared error.
  Exercise 2 : exploratory analysis of the `ausbeer` series (quarterly
               Australian beer production) from the `fpp2` package.

REQUIREMENTS
------------

- Quarto
- R, with the `fpp2` and `ggplot2` packages installed
- lualatex (for PDF rendering)

HOW TO RENDER
-------------

  quarto render assignment4.qmd

  This runs all the R code and produces assignment4.pdf. The Monte
  Carlo experiment (5000 replications x 9 cases) is cached, so the
  first render is slower; later renders skip it unless that code
  changes, and finish in a few seconds.
