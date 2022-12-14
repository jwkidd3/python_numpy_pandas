[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/guiwitz/NumpyPandas_course/54488164b462644baf601875be69cc911eda9615?urlpath=lab)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guiwitz/NumpyPandas_course/blob/colab)


# Introduction to Numpy and Pandas

This repository contains Jupyter notebooks introducing beginners to the Python packages Numpy and Pandas. The material has been designed for people already familiar with Python but not with its "scientific stack".

## Content
The course has the following content:

### Numpy
- [Numpy arrays:](01-DA_Numpy_arrays_creation.ipynb): what they are and how to create, import and save them
- [Maths with Numpy arrays](02-DA_Numpy_array_maths.ipynb): applying functions to arrays, doing basic statistics with arrays
- [Numpy and Matplotlib](03-DA_Numpy_matplotlib.ipynb): Basics of plotting Numpy arrays with Matplotlib
- [Recovering parts of arrays](04-DA_Numpy_indexing.ipynb): Using array coordinates to extract information (indexing, slicing)
- [Combining arrays](05-DA_Numpy_combining_arrays.ipynb): Assembling arrays by concatenation, stacking etc. Combining arrays of different sizes (broadcasting)
  
### Pandas
- [Introduction to Pandas](06-DA_Pandas_introduction.ipynb): What does Pandas offer?
- [Pandas data structures](07-DA_Pandas_structures.ipynb): Series and dataframes
- [Importing data to Pandas](08-DA_Pandas_import_plotting.ipynb): Importing data tables into Pandas (from Excel, CSV) and plotting them
- [Pandas operations](09-DA_Pandas_operations.ipynb): Applying functions to the contents of Pandas dataframes (classical statistics, ```apply``` function etc.)
- [Combining Pandas dataframes](10-DA_Pandas_combine.ipynb): Using concatenation or join operations to combine dataframes
- [Analyzing Pandas dataframes](11-DA_Pandas_splitting.ipynb): Split dataframes into groups (```groupy```) for category-based analysis
- [A real-world example](12-DA_Pandas_realworld.ipynb): Complete pipeline including data import, cleaning, analysis and plotting and showing the nitty-gritty issues one often faces with real data


In the Pandas part, we use some data provided publicly by the Swiss National Science foundation at this link: http://p3.snf.ch/Pages/DataAndDocumentation.aspx#DataDownload. The examples of analysis on these data **are in no way confirmed or validated by the SNSF and are entirely the work of Guillaume Witz, Science IT Support, Bern University**.

