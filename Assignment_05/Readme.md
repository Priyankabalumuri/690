# DATA ANALYSIS
The process of inspecting, cleansing, transforming and modeling data with the goal of discovering useful information, informing conclusion and supporting decision-making.

# Tools for Data Analysis
•	Auto-Managed Closed Tools : Qlik, Tableau, Looker, Zoho Analytics

•	Programming Languages : Python, R, Julia

# Auto-Managed Closed Tools
•	Advantages: Easy to handle things in more professional way

•	Disadvantages : Closed source, cost-effective, minimalized

# Programming Languages
•	Advantages : Open source, free, extremely powerful

•	Disadvantages : Steep learning curve

# Why is python used for data analysis?
•	Easy to learn

•	Have powerful libraries

•	Free and open source

•	Great community, documentation and conferences

# When to choose R?
•	When there is a need for R studio

•	When dealing with advanced statistical methods

•	When there is a need for extreme perfomance

# The process of data analysis
•	Data extraction - Getting the data

•	Data cleaning - Dealing with missing values, empty data and incorrect types

•	Data wrangling - Rearrange and reshape the data

•	Data analysis - Exploration of data(building statistical models and visualization)

•	Action - Building machine learning models

# Python Libraries
• Pandas: The cornerstone of our Data Analysis job with Python matplotlib: The foundational library for visualizations. Other libraries we’ll use will be built on top of matplotlib.

•	 Numpy: The numeric library that serves as the foundation of all calculations in Python.

•	Seaborn: A statistical visualization tool built on top of matplotlib.

• Statsmodels: A library with many advanced statistical functions.

•	Scipy: Advanced scientific computing, including functions for optimization, linear algebra, image processing and much more.

• Scikit-learn: The most popular machine learning library for Python (not deep learning)

# What is Jupyter Notebook and used for?

The Jupyter Notebook is an open-source web application that allows data scientists to create and share documents that integrate live code, equations, computational output, visualizations, and other multimedia resources, along with explanatory text in a single document.

# Everything in a cell

Jupyter notebooks are organized as a set of "cells". Each cell can contain different types of content (markdown text, Python code, R code, etc.) The current cell containing text is a markdown cell, cells with code are code cells, as displayed below.

# Finding Unique Values

The first step to clean invalid values is to notice them, then identify them and finally handle them appropriately (remove them, replace them, etc). Usually, for a "categorical" type of field (like Sex, which only takes values of a discrete set ('M', 'F')), we start by analyzing the variety of values present. For that, we use the unique() method.

# Duplicates

Checking duplicate values is extremely simple. It'll behave differently between Series and DataFrames. 
The two most important methods to deal with duplicates are duplicated (that will tell you which values are duplicates) and drop_duplicates (which will just get rid of duplicates

# Reading data with Pandas

Probably one of the most recurrent types of work for data analysis: public data sources, logs, historical information tables, exports from databases. So the pandas library offers us functions to read and write files in multiple formats like CSV, JSON, XML and Excel's XLSX, all of them creating a DataFrame with the information read from the file.

We'll learn how to read different type of data including:

CSV files (.csv) Raw text files (.txt) JSON data from a file and from an API Data from a SQL query over a database

# The read_csv method

The first method we'll learn is read_csv, that let us read comma-separated values (CSV) files and raw text (TXT) files into a DataFrame.

The read_csv function is extremely powerful and you can specify a very broad set of parameters at import time that allow us to accurately configure how the data will be read and parsed by specifying the correct structure, enconding and other details. The most common parameters are as follows:

•	filepath: Path of the file to be read.

•	sep: Character(s) that are used as a field separator in the file.

•	header: Index of the row containing the names of the columns (None if none).

•	index_col: Index of the column or sequence of indexes that should be used as index of rows of the data.

• names: Sequence containing the names of the columns (used together with header = None).

• skiprows: Number of rows or sequence of row indexes to ignore in the load.

• na_values: Sequence of values that, if found in the file, should be treated as NaN.

•	dtype: Dictionary in which the keys will be column names and the values will be types of NumPy to which their content must be converted.

• parse_dates: Flag that indicates if Python should try to parse data with a format similar to dates as dates. You can enter a list of column names that must be joined for the parsing as a date.

•	date_parser: Function to use to try to parse dates.

•	nrows: Number of rows to read from the beginning of the file.

•	skip_footer: Number of rows to ignore at the end of the file.

•	encoding: Encoding to be expected from the file read.

•	squeeze: Flag that indicates that if the data read only contains one column the result is a Series instead of a DataFrame.

•	thousands: Character to use to detect the thousands separator.

• decimal: Character to use to detect the decimal separator.

•	skip_blank_lines: Flag that indicates whether blank lines should be ignored.

