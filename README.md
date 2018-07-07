# Antipsychotic-induced weight gain and the striatum

# Author
Philipp Homan <phoman1 at northwell dot edu>

# Getting Started
This repository contains all the data and analysis
code to reproduce the manuscript "Striatal volume and functional
connectivity predict weight gain in early-phase schizophrenia". These
instructions describe how to obtain a copy of the project up and running
on your local machine for reproducing the analysis described in the
manuscript. The repository contains a Makefile which reflects the
dependencies of the analysis; analysis, figures and manuscript can be
produced by simply typing 'make' from the Unix command line.

## Prerequisites
The project was developed and tested on a Linux Ubuntu 17.10 machine. To
produce the manuscript from the command line, GNU emacs and texlive must
be installed together with some additional emacs and texlive
packages. Specifically, the following software and associated libraries
are required:

### texlive
-   xetex
-   latexmk

### emacs
-   org-mode
-   ess
-   org-ref

### R
-   pacman
-   R.matlab
-   cowplot
-   ellipse
-   astsa
-   magick
-   here
-   png
-   grid
-   flexmix
-   DescTools
-   boot
-   lme4
-   lsmeans
-   graphics
-   tibble
-   tidyr
-   ggplot2
-   dplyr
-   MASS

# Installing
Download the tarball bmi.tgz and run 'tar xvfz bmi.tgz' from the command
line.

# Running the analysis
Change to the bmi directory and run 'make analysis'.

# Producing the figures
Change to the bmi directory and run 'make figures'. The figures can then
be found in output/figures.

# Producing the manuscript
Change to the bmi directory and run 'make manuscript'. The manuscript
will be in src/bmi_ms.pdf</sub>

# Built With
Org-mode 9.1.7.
