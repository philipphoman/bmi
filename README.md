
# Antipsychotic-induced weight gain and the striatum



## Author

Philipp Homan <phoman1 at northwell dot edu>


## Full author list

Philipp Homan, Dr. Miklos Argyelan, Dr. Christina Fales, Dr. Anita
Barber, Dr. Pamela DeRosse, Dr. Philip Szeszko, Dr. Delbert Robinson
, Dr. Todd Lencz, Anil Malhotra


## Acknowledgments

The authors thank Dr. Lauren Hanna and Dr. Juan Gallego for their
careful clinical oversight of the study. They acknowledge their
patients, their patients' families, and their psychiatry research
support staff.


## Getting Started

This repository contains all the data and analysis code to reproduce the
manuscript *Striatal volume and functional connectivity correlate with
weight gain in early-phase psychosis*. These instructions describe how
to obtain a copy of the project up and running on your local machine for
reproducing the analysis described in the manuscript. The repository
contains a Makefile which reflects the dependencies of the analysis;
analysis, figures and manuscript can be produced by simply typing 'make'
from the Unix command line.


### Prerequisites

All analyses were conducted with the R software 
R version 3.6.0 (2019-04-26). Mixed models were estimated
using the lme4 library. The full session info under R can be found at
the end of this file


## Installing

Clone the repository or download the zip file.


## Running the analysis

Change to the bmi directory and run 'make analysis'.


## Producing the figures

Change to the bmi directory and run 'make figures'. The figures can then
be found in output/figures.


## Producing the manuscript

Change to the bmi directory and run 'make manuscript'. The manuscript
will be in src/.


## Built With

Ubuntu 18.04.2 LTS on emacs
25.2.2 and org-mode
9.1.7.


## Session info

