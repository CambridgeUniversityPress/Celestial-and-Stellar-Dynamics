# *Celestial and Stellar Dynamics*

Jupyter notebooks, python code, and selected data files and sources for the figures from 
[*Celestial and Stellar Dynamics*](https://www.cambridge.org/highereducation/books/celestial-and-stellar-dynamics/8EC981C3B1938BFCA749AD76C496C4EC) by Barbara Ryden.

**Publication expected in February 2025...**

[!["CSD Cover"](Misc/CSD_Cover_512.png?raw=true "Celestial and Stellar Dynamics")](https://www.cambridge.org/highereducation/books/stellar-structure-and-evolution/B6F803BC5085E8736B640F9ED4A0FA27)

## Overview
*Celestial and Stellar Dynamics* by Barbara S. Ryden is the third volume in *The Ohio State Astrophysics Series* of 
textbooks published by Cambridge University Press.  The audience for this series is graduate students and upper-level undergraduates studying
astronomy and physics.

Most of the original figures in this book were created by the Richard Pogge (OSU), the technical editor of the OSAS book series, the majority of 
which are plots of data or calculations made using Python programs implemented as Jupyter notebooks. We are making all the notebooks available 
on GitHub as an ancillary to the book.

Instructors and students using *Celestial and Stellar Dynamics* are welcome to use these notebooks to make high-resolution versions
of the book figures for presentations, adapt them for use in class, or to use as the basis for problem sets or projects in courses 
adopting this book.  Over time we hope to collect and present other notebooks that will enable further explorations of topics in the book, 
become part of computational problem sets or individual and group projects, etc. This way, the figures become a starting point for learning
and new explorations rather than being frozen into print.

## Software Requirements

All notebooks were developed in Python 3 using the [Anaconda Python distribution](https://www.anaconda.com). 

Required packages are numpy, scipy, pandas, matplotlib, and astropy, all part of Anaconda. 

LaTeX is required for math symbols in the notebooks.

**Note**: Please update
matplotlib to later than version 3.8 as the contour routines changed significantly compared to previous
versions and we made use of some low-level features that required changes to the code that are not 
backwards compatible with older versions.

### Optional Packages

Some of the figures in the book use the [galpy](https://github.com/jobovy/galpy) Python package for galactic dynamics by Jo Bovy.
Because `galpy` is relatively efficient and easy to install, we do all the `galpy` calculations in-situ in the notebooks.

Another set of figures uses the Python version of the [rebound](https://rebound.readthedocs.io/en/latest/) N-body integrator package
developed by Hanno Rein and collaborators. Because installation of `rebound` is more involved and runtimes can be long, 
we provide pre-computed `rebound` models for the relevant notebooks, but inlclude the notebooks that ran `rebound` for the figures
as a supplement.

The `galpy` and `rebound` packages have active user communities and there are many examples and guides to help you explore these
powerful programs on your own.

Supplementary exercises for students using `galpy` and `rebound` are being contemplated and may be released later on this 
repository.

## Downloads

### Download and Install

To download a copy of this repository onto your local computer, go to the folder on your computer where you want to install it and type

> `git clone https://github.com/CambridgeUniversityPress/Celestial-and-Stellar-Dynamics`

This will create the `Celestial-and-Stellar-Dynamics` folder containing the entire repository.  You may rename this repository after
installation to shorten the name if you wish (e.g., `/path/to/wherever/CSD`).

### Update the notebooks and data

To update your copy, go into the top-level folder you created above (e.g., `/path/to/wherever/CSD`) and type

> `git pull`

If there are no updates, your local copy will be unaffected.

## Use and Attribution

The notebooks and their contents are original works of the authors and often include data obtained from public archives or from 
professional colleagues (always from published sources).  We ask that users preserve all literature citations to the original work
from which such data were derived, and give proper credit when using them. If you use these notebooks, please make
reference to the *Celestial and Stellar Dynamics* book and this repository.

### License Notice

All files in this repository are licensed under a [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/), 
to foster broader use of the notebooks and their data by teachers and students.

