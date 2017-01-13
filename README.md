# Jackson et al., 2017

**Phillipsite and Al-tobermorite produced by cementitious water-rock reactions in Roman marine concrete**

*Marie D. Jackson, Sean R. Mulcahy, Heng Chen, Yao Li, Qinfei Li, Piergiulio Cappelletti, Hans-Rudolf Wenk*

[doi:](http://doi.org/)

## Summary
This repository contains electron probe microanalysis (EPMA) data and python jupyter notebooks to plot ternary diagrams in Figures 3 and 4 of Jackson et al., 2017.

**Cite as:**

Jackson, M.D., Mulcahy, S.R., Chen, H., Li, Y., Li, Q., Cappelletti, P., and Wenk, H.-R., 2017, Phillipsite and Al-tobermorite produced by cementitious water-rock reactions in Roman marine concrete, *American Mineralogist*, doi:[]().

Code and data set archived on Zenodo: 

## Project Folders

- [src](https://github.com/srmulcahy/2017-jackson-ammin/tree/master/src): python jupyter notebooks
    - *[phillipsite-ternary.ipynb](https://github.com/srmulcahy/2017-jackson-ammin/blob/master/src/phillipsite-ternary.ipynb)*: Calculate formula units and uncertainties from EPMA data. Plot ternary phillipsite compositions shown in mansucript figures
    - *[tobermorite-ternary.ipynb](https://github.com/srmulcahy/2017-jackson-ammin/blob/master/src/tobermorite-ternary.ipynb)*: Calculate formula units and uncertainties from EPMA data. Plot ternary tobermoreite compositions shown in mansucript figures
- [data](https://github.com/srmulcahy/2017-jackson-ammin/tree/master/data): raw data used in analysis
    - *phillipsite-oxide.csv*: phillipsite EPMA weight% oxides analyzed in this study
    - *phillipsite-oxide-2sigma.csv*: 2-sigma absolute uncertainty of analyzed phillipsite EPMA weight% oxides
    - *phillipsite-cation.csv*: Phillipsite formula units calcuated from the EPMA weight% oxide
    - *phillipsite-cation-error.csv*: 2-sigma absolute uncertainty for calculated phillipsite formulas
    - *phillipsite-cations-plotting.csv*: Phillipsite formula units grouped by sample plotting category
    - *phillipsite-oxide-literature.csv*: Published EPMA phillipsite compositions   
    - *tobermorite-oxide.csv*: tobermorite EPMA weight% oxides analyzed in this study
    - *tobermorite-oxide-sigma.csv*: 1-sigma absolute uncertainty of analyzed tobermorite EPMA weight% oxides
    - *tobermorite-cation.csv*: Tobermorite formula units calcuated from the EPMA weight% oxide
    - *tobermorite-cation-error.csv*: 2-sigma absolute uncertainty for calculated tobermorite formulas
    - *tobermorite-cations-plotting.csv*: Tobermorite formula units grouped by sample plotting category
    - *tobermorite-literature.csv*: Published EPMA tobermorite compositions 
- [figs](https://github.com/srmulcahy/2017-jackson-ammin/tree/master/figs): svg plots from python scripts
    - *phillipsite-CMNK-jacksonetal.svg*: Ca+Mg-Na-K ternary of analyzed phillipsite compositions
    - *phillipsite-CMNK-published.svg*: Ca+Mg-Na-K ternary of previously published phillipsite compositions
    - *phillipsite-SDM-jacksonetal.svg*: Si-D-M ternary of analyzed phillipsite compositions
    - *phillipsite-SDM-published.svg*: Si-D-M ternary of analyzed phillipsite
    - *tobermorite-SCA-jacksonetal.svg*: Si-Ca-Al ternary of analyzed tobermorite compositions
    - *tobermorite-SCA-published.svg*: Si-Ca-Al ternary of prevoiously published tobermorite compositions
    - *tobermorite-SCNK-jacksonetal.svg*: Si+Ca-Na-K ternary of analyzed tobermorite compositions
    - *tobermorite-SCNK-published.svg*: Si+Ca-Na-K ternary of prevoiously published tobermorite compositions

## Python Packages

The code in this repository was written with [Python 3](https://www.python.org/download/releases/3.0/) using the packages below.  The easiest way to install the software on any operating system is with [Anaconda](https://www.continuum.io/downloads) or [Miniconda](http://conda.pydata.org/miniconda.html).

- [ipython/jupyter](https://ipython.org/) Pérez, F., and Granger, B.E., 2007, IPython: a system for interactive scientific computing: Computing in Science & Engineering, v. 9, no. 3, p. 21–29.
- [matplotlib](http://matplotlib.org/) Hunter, J.D., and others, 2007, Matplotlib: A 2D graphics environment: Computing in science and engineering, v. 9, no. 3, p. 90–95.
- [numpy](http://www.numpy.org/) Van Der Walt, S., Colbert, S.C., and Varoquaux, G., 2011, The NumPy array: a structure for efficient numerical computation: Computing in Science & Engineering, v. 13, no. 2, p. 22–30.
- [pandas](http://pandas.pydata.org/) McKinney, W., and others, 2010, Data structures for statistical computing in python, in Proceedings of the 9th Python in Science Conference, p. 51–56.
- [uncertainties](https://pythonhosted.org/uncertainties/) Lebigot, E.O., 2013, Uncertainties: a Python package for calculations with uncertainties: URL http://pythonhosted. org/uncertainties,.
- [python-ternary](https://github.com/marcharper/python-ternary) Harper, M., Weinstein, B., Simon, C., chebee7i, Swanson-Hysell, N., Badger, T.G., Greco, M., and Zuidhof, G. python-ternary: Ternary Plots in Python: Zenodo, doi: 10.5281/zenodo.34938.
- [seaborn](http://seaborn.pydata.org/) Waskom, M., Botvinnik, O., drewokane, Hobson, P., David, Halchenko, Y., Lukauskas, S., Cole, J.B., Warmenhoven, J., Ruiter, J. de, Hoyer, S., Vanderplas, J., Villalba, S., Kunter, G., et al. seaborn: v0.7.1 (June 2016): Zenodo, doi: 10.5281/zenodo.54844.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a><br />This work is
licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by/3.0/">Creative Commons Attribution
3.0 Unported License</a>.