[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rpmanser/data_analysis_workshop/HEAD)

# Python Data Analysis Workshop

This workshop provides a brief introduction to Python libraries that provide tools for quantitative data analysis and data science. The target audience is for people with beginner to intermediate programming skill who wish to learn the basics of data analysis using Python.

## Installation

No installation is required for this workshop, as it will be delivered via Binder. However, if you wish to install the environment on your own machine, install Anaconda (or an equivalent) and run the following command:

`conda create -f environment.yml`

This will create an environment named `data_analysis` with all of the libraries used in this workshop.

## Notebooks

The included notebooks build upon each other in the following order and cover these topics:

* An introduction to the Jupyter notebook environment and notebook structure - `getting_started.ipynb`
* Brief introduction to Python as it pertains to the workshop -- `intro_to_python.ipynb`
* Introduction to NumPy arrays and plotting data using Matplotlib -- `numpy_and_matplotlib.ipynb`
* Introduction to pandas and working with tabular data -- `pandas_and_scikit_learn.ipynb`
* Cleaning, exploring, and working with real data -- `data_analysis.ipynb`

## Data

Datasets are created within notebooks or, in the case of `data_analysis.ipynb`, downloaded from a remote source. The downloaded file is about 35 MB.

## References and further reading

This workshop was compiled from multiple resources, all of which are listed below.

* Unidata introduction to Python https://unidata.github.io/python-training/python/intro-to-python/
* Software Carpentry https://software-carpentry.org/lessons/
* Unidata Python workshop https://unidata.github.io/python-training/workshop/workshop-intro/
* Creating models https://realpython.com/linear-regression-in-python/
* SciPy for scientific computing https://scipy-lectures.org/
