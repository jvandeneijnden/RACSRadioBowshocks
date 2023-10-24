[![DOI](https://zenodo.org/badge/472272277.svg)](https://zenodo.org/doi/10.5281/zenodo.10038514)

# Analysis reproduction repository for the search for bow shock from massive runaway stars in RACS

![The bow shock G3 in radio and IR](Figure1_2/G3.BOTH.png?raw=true "The bow shock G3 in radio and IR")

## Based on Van den Eijnden et al. (2022), MNRAS to be submitted.
The full paper can be found on https://arxiv.org/abs/2203.10842 (open access).

This repository contains two Jupyter notebooks and all required underlying data to produce the images and calculations in the paper "Radio detections of IR-selected runaway stellar bow shocks". In order to run the Notebooks, check the software requirements below, clone the repository, and run through each cell. The motivations for the performed calculations and plotting settings are also included to certain extend, although we refer to the main paper for full details.

Please get in touch via email (jakob.vandeneijnden [at] st-hildas.ox.ac.uk) or github with questions. 

If this repository is useful for your own research, in addition to citing the original paper, please consider including a note to this repository as well.

## Software requirements

This notebook is written in Python2.7; updates to Python3.x should be straightforward but are left to the user.

In addition, this notebook makes use of the following packages, where the associated versions were used in the paper calculations. 

- numpy v1.15.4
- matplotlib v2.2.3
- aplpy v1.1.1
- scipy v1.1.0
- astropy v2.0.9

As noted in the Plotting Fields notebook, the created .png images are combined using external software into the composite images shown in the paper.
