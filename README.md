# pycowview
Python implementation of methods to work with real-time location system (RTLS) data from GEA CowView

This repository contains core functions that could be used for specific analyses. The code for `pycowview` is a work in progress, so feel free to suggest your changes.

## Getting started
In order to access the `PyCowView` code, please add a new submodule to your repository using the `git submodule add https://github.com/CSI-DT/PyCowView` command.

Then you can access the `pycowview` code as follows:
```
from pycowview.plot import plot_barn

plot_barn('data/barn.csv')
```
