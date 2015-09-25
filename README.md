# Pandas Tutorial
Python Library for Data Exploration

- Romain Lepert


### Tutorial

1. [DataFrame and Series](Pandas I - Series and DataFrames.ipynb)
2. [Working with DataFrames](Pandas II - Working with DataFrames.ipynb)
3. Datetime Series

### Case Study

- [MovieLens](Case Study - MovieLens.ipynb)

#### Introduction to Pandas

**Pandas** is a Python package providing fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for
doing practical, **real world** data analysis in Python. Additionally, it has the broader goal of becoming **the most powerful and flexible open source data analysis / manipulation tool available in any language**. It is already well on
its way toward this goal.

Here are some of pandas main features:

- Easy handling of [missing data][missing-data] (represented as `NaN`) in floating point as well as non-floating point data
- Size mutability: columns can be [inserted and deleted][insertion-deletion] from DataFrame and higher dimensional objects
- Automatic and explicit [data alignment][alignment]: objects can be explicitly aligned to a set of labels, or the user can simply ignore the labels and let `Series`, `DataFrame`, etc. automatically align the data for you in computations
- Powerful, flexible [group by][groupby] functionality to perform split-apply-combine operations on data sets, for both aggregating and transforming data
- Make it [easy to convert][conversion] ragged, differently-indexed data in other Python and NumPy data structures into DataFrame objects
- Intelligent label-based [slicing][slicing], [fancy indexing][fancy-indexing], and [subsetting][subsetting] of large data sets
- Intuitive [merging][merging] and [joining][joining] data sets
- Flexible [reshaping][reshape] and [pivoting][pivot-table] of data sets
- [Hierarchical][mi] labeling of axes (possible to have multiple labels per tick)
- Robust I/O tools for loading data from [flat files][flat-files] (CSV and delimited), [Excel files][excel], [databases][db], and saving/loading data from the ultrafast [HDF5 format][hdfstore]
- [Time series][timeseries]-specific functionality: date range generation and frequency conversion, moving window statistics, moving window linear regressions, date shifting and lagging, etc.

[missing-data]: http://pandas.pydata.org/pandas-docs/stable/missing_data.html#working-with-missing-data
[insertion-deletion]: http://pandas.pydata.org/pandas-docs/stable/dsintro.html#column-selection-addition-deletion
[alignment]: http://pandas.pydata.org/pandas-docs/stable/dsintro.html?highlight=alignment#intro-to-data-structures
[groupby]: http://pandas.pydata.org/pandas-docs/stable/groupby.html#group-by-split-apply-combine
[conversion]: http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe
[slicing]: http://pandas.pydata.org/pandas-docs/stable/indexing.html#slicing-ranges
[fancy-indexing]: http://pandas.pydata.org/pandas-docs/stable/indexing.html#advanced-indexing-with-ix
[subsetting]: http://pandas.pydata.org/pandas-docs/stable/indexing.html#boolean-indexing
[merging]: http://pandas.pydata.org/pandas-docs/stable/merging.html#database-style-dataframe-joining-merging
[joining]: http://pandas.pydata.org/pandas-docs/stable/merging.html#joining-on-index
[reshape]: http://pandas.pydata.org/pandas-docs/stable/reshaping.html#reshaping-and-pivot-tables
[pivot-table]: http://pandas.pydata.org/pandas-docs/stable/reshaping.html#pivot-tables-and-cross-tabulations
[mi]: http://pandas.pydata.org/pandas-docs/stable/indexing.html#hierarchical-indexing-multiindex
[flat-files]: http://pandas.pydata.org/pandas-docs/stable/io.html#csv-text-files
[excel]: http://pandas.pydata.org/pandas-docs/stable/io.html#excel-files
[db]: http://pandas.pydata.org/pandas-docs/stable/io.html#sql-queries
[hdfstore]: http://pandas.pydata.org/pandas-docs/stable/io.html#hdf5-pytables
[timeseries]: http://pandas.pydata.org/pandas-docs/stable/timeseries.html#time-series-date-functionality

To dive deeper into the package, check out [pandas documentation](http://pandas.pydata.org/pandas-docs/stable/).