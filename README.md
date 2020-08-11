The code was copied from https://github.com/pymc-devs/resources repository. It's here for educational purpose only.

# Statistical Rethinking (second edition) with Python and PyMC3

[Statistical Rethinking](http://xcelab.net/rm/statistical-rethinking/) is an incredible introductory book to Bayesian Statistics. It follows a [_Jaynesian_](https://en.wikipedia.org/wiki/Edwin_Thompson_Jaynes) and practical approach with very good examples and clear explanations.

In this repository we port [the book's original code in R and Stan](https://github.com/rmcelreath/rethinking) to Python and PyMC3. We attempt to reproduce the examples as faithfully as possible while expressing them in a _Pythonic_ and _PyMC3onic_ way.

## Display notebooks
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/pymc-devs/resources/master?filepath=Rethinking_2)
[<img src="http://nbviewer.jupyter.org/static/img/nav_logo.svg" width=120>](http://nbviewer.jupyter.org/github/pymc-devs/resources/blob/master/Rethinking_2)


## Installing the dependencies

To install the dependencies to run these notebooks, you can use [Anaconda](https://www.continuum.io/downloads). Once you have installed Anaconda, run:

    conda env create -f environment.yml

to install all the dependencies into an isolated environment. 

Activate the environment by running:

    source activate stat-rethink2-pymc3
