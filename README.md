# pandas

Materials for teaching the introductory pandas workshop at UC Berkeley's D-Lab.

## Set Up

For this workshop we'll be using a Jupyter notebook.

### Software for the workshop

The best learning experience happens when you can edit and run code. So, please have pandas, Matplotlib, and Jupyter or IPython installed. There are several options for getting your environment set up.

1. [Anaconda](http://continuum.io/downloads) with Python 3.5+ (2.7 is okay).
2. Python 3.5+ (2.7 is okay) and required packages installed using a package manager, such as `conda` (via [Miniconda](https://conda.io/docs/install/quick.html)) or [pip](https://pip.pypa.io/en/stable/installing.html); you must install IPython 3.0+ with notebook support or IPython 4.0+/Jupyter 1.0+, pandas 0.17+, and Matplotlib 1.3+.
3. (Perhaps as a last resort) [BCE Summer 2015](http://bce.berkeley.edu/install.html).

Both Anaconda and BCE distributions will install everything you need for this workshop (but BCE will most likely be out of date). If you decide to use `pip`, you can do the following (or for Miniconda, replace `pip` with `conda`):

```
# Install pandas and Matplotlib
$ pip install pandas matplotlib

# Install Jupyter
$ pip install --upgrade jupyter
```

### Files for the workshop

Once those are installed, you should get the necessary files for this workshop, which are contained in this repository. Get them by doing the following:

```
# Clone this repository
$ git clone https://github.com/dlab-berkeley/introduction-to-pandas.git

# Navigate to the repo
$ cd introduction-to-pandas

# Start the interactive session
$ jupyter notebook

# ...alternatively (older versions of IPython)
$ ipython notebook
```

## Outline

For this workshop, we'll go through an example using European unemployment data. We'll load, view, and modify the data as well as calculate some descriptive statistics. The idea is to get a sense of what it would be like to use pandas as part of your workflow.

We plan to cover:

* pandas data structures
* loading data
* subsetting and filtering
* calculating summary statistics
* dealing with missing values
* merging data sets
* creating new variables
* basic plotting
* exporting data

## Further resources

[pandas Documentation](http://pandas.pydata.org/pandas-docs/stable/)
