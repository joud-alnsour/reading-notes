# Pandas in 10
- import pandas by using 'import pandas as pd'
- create a series ex:
   - input: s = pd.Series([1,3,5, np.nan,6,8])
   - output: s (1,2,5,NaN,6,8)
- Create a DataFrame by passing a NumPy array, with a datetime index and labeled
- Create a DataFrame by passing a dict of objects that can be converted to series-like
- use df.head() and df.tail() to see the start and end values in a dataframe
- use df.index and df.columns to see the index and columns respectively
- DataFrame.to_numpy() gives a NumPy representation of the underlying data. Note that this can be an expensive operation when your DataFrame has columns with different data types
- The fundamental difference between pandas and NumPy, NumPy arrays have one dtype for the entire array, while pandas DataFrames have one dtype per column
- describe() shows a quick statistic summary of your data
- Selecting via [], which slices the rows.
- pandas primarily uses the value np.nan to represent missing data. It is by default not included in computations.
- Series is equipped with a set of string processing methods in the str attribute that make it easy to operate on each element of the array, as in the code snippet below. Note that pattern-matching in str generally uses regular expressions by default (and in some cases always uses them)
- pandas provides various facilities for easily combining together Series and DataFrame objects with various kinds of set logic for the indexes and relational algebra functionality in the case of join / merge-type operations
- With a “stacked” DataFrame or Series (having a MultiIndex as the index), the inverse operation of stack() is unstack(), which by default unstacks the last level
- pandas has simple, powerful, and efficient functionality for performing resampling operations during frequency conversion (e.g., converting secondly data into 5-minutely data)
- We use the standard convention for referencing the matplotlib API:
import matplotlib.pyplot as plt
- The close() method is used to close a figure window.
- df.to_csv("example.csv") to write to a csv
- pd.read_csv("example.csv") to read as a csv file
- df.to_excel("example.xlsx", sheet_name="Sheet1") to write to an excel file
- pd.read_excel() to read from an excel file




[Page Link 1](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)<br>

[Page Link 2](https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/index.html)<br>

[Page Link 3](https://realpython.com/learning-paths/pandas-data-science/)

