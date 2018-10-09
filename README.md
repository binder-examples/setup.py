# python package with setup.py

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/binder-examples/setup.py/master?filepath=example_notebook%2Fimport_mypackage.ipynb)

A Binder-compatible repo with a python package and a `setup.py` file.


## Notes

It is convenient to provide an [example Jupyter notebook ](https://github.com/binder-examples/setup.py/blob/master/example_notebook/import_mypackage.ipynb) for a new package and add the hooks necessary to run the example with Binder. However, normally the package will not be included in the python path. To do that, one needs a `setup.py` for the package (see [binder docs](https://mybinder.readthedocs.io/en/latest/using.html#setup-py)). Once this is done, it is possible to import the package in a notebook running within Binder. 

This setup.py was originally adapted from [https://github.com/kennethreitz/setup.py](https://github.com/kennethreitz/setup.py) by @cranmer
