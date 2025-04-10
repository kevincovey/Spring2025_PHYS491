# Data compilations and figure-generating scripts for "Star Clusters Across Cosmic Time" #

This repository contains all of the data compilations, and the notebooks required to process them and generate figures, from the review "Star Clusters Across Cosmic Time" by Krumholz, McKee, & Bland-Hawthorn (2019, submitted to Annual Reviews of Astronomy & Astrophysics). The figures themselves are also included.

### Contents and layout ###

This repository contains a main directory and two sub-directories. The main directory contains the Jupyter/python notebooks that process the data and generate the figures. The notebooks included are:

* ``cluster_demographics.ipynb`` -- generates figures 5 - 8 of the review (image files ``cmf.pdf``, ``caf.pdf``, ``gamma.pdf``, and ``mw_age_dist.pdf``)
* ``color_evol.ipynb`` -- generates figure 3 of the review (``color_evol.pdf``)
* ``epsff.ipynb`` -- generates figures 10 and 11 of the review (``epsff.pdf`` and ``epsff_meth.pdf``)
* ``mass_radius.ipynb`` -- generates figures 9, 12, and 14 of the review (``mass_radius.pdf``, ``mass_radius_feedback.pdf``, and ``clump_cluster.pdf``)
* ``orion_plot.ipynb`` -- generates figures 2 and 13 of the review (``orion.pdf`` and ``orion_age.pdf``)
* ``postage_stamps.ipynb`` -- generates figure 1 of the review (``postage_stamps.pdf``)
* ``tidal.ipynb`` -- generates figure 15 of the review (``tidal_3d.pdf`` and ``tidal_xz.pdf``)

The two subdirectories are ``data`` and ``figures``. The ``data`` directory contains all the data files required by the notebooks (with the exception of ``postage_stamps.ipynb``, which downloads the images it needs automatically because they are too large to include in the repository); see the explanatory documentation in each notebook for a list of which data sets they use, and where those data come from. The ``figures`` directory contains the output figures.

### Dependencies ###

The notebooks included are standard Jupyter notebooks running python code; the code should be compatible with either python 2 or 3. Almost all notebooks make use of the following python packages:

* [numpy](http://www.numpy.org/)
* [scipy](https://www.scipy.org/)
* [astropy](http://www.astropy.org/)
* [matplotlib](https://matplotlib.org/)

In addition, certain notebooks require the following packages:

* [Pillow](https://python-pillow.org/)
* [SLUG](https://bitbucket.org/krumholz/slug2)

These additional requirements are described in the documentation for the individual notebooks.

### License ###

This repository is distributed under the terms of the GPL v3. A copy of the license is included in the repository.

### Contact information ###

Please contact Mark Krumholz, mark.krumholz@anu.edu.au, with any questions.