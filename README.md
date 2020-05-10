# D-Lab Introduction to Pandas workshop

This repository contains materials for the introductory pandas workshop at the UC Berkeley D-Lab.

### 1. Software for the workshop

The best learning experience happens when you can edit and run code. So, please have Python Anaconda Distribution 3.7, pandas, matplotlib, and Jupyter installed before the start of the workshop. Follow the steps below to setup your environment: 

1. [Click here to download Python Anaconda 3.7 Distribution](https://www.anaconda.com/products/individual), although 3.6 is also okay if you already have it installed. Scroll down to the "Anaconda Installers" section and click the "Graphical Installer" option that corresponds to your operating system. 

2. If you are using Terminal (Mac) or GitBash (PC), you can pip install the necessary packages by typing: 

`$ pip install pandas matplotlib jupyter`

> Windows users only - if you wish to emulate the Bash programming language found in Mac users' "Terminal" application, [click here to download GitBash](https://git-scm.com/downloads), a Unix command-line environment for Windows users. 

Alternatively, you can install these packages by adding a cell to the top of your Jupyter Notebook and typing: 

`!pip install pandas matplotlib jupyter`

### 2. Files for the workshop

Once the software is installed, download the necessary files for the workshops which are contained in this repository. Get them by doing the following:

1. Click the green "Clone or Download" button
2. Click "Download Zip"
3. Extract this .zip file someplace familiar, such as your Desktop. 

Or, if you are a Git user you can simply clone this repository

`$ git clone git@github.com:dlab-berkeley/introduction-to-pandas.git`

### 3. Open a Jupyter Notebook

1. Open the "Anaconda Navigator" application and click "Launch" under Jupyter Notebook

or

Navigate to the respository using Terminal or Gitbash and type

`$ cd introduction-to-pandas`

then

`$ jupyter notebook` or `python3 -m notebook`

This will open a blank notebook for you to use as a scratch space is you desire. Open the file "introduction-to-pandas.ipynb" to access the tutorial.

### 4. Outline

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

### 5. Further resources

[Getting started with pandas](http://pandas.pydata.org/pandas-docs/stable/)

[10 minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html)

[Visualization with pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html)
