Tuples are immutable. eg. (12345, 54321, 'hello!')\ 

A set is an unordered collection with no duplicate elements. {'orange', 'banana', 'pear', 'apple'}. Note: to create an empty set you have to use set(), not {}.\

Dictionary is a set of key: value pairs. Keys are unique (within one dictionary). {'jack': 4098, 'sape': 4139}

Enumerate - for i, v in enumerate(['tic', 'tac', 'toe']):
    print(i, v)
    0 tic
    1 tac
    2 toe\

Series: a one-dimensional labeled array holding data of any type such as integers, strings, Python objects etc.\

DataFrame: a two-dimensional data structure that holds data like a two-dimension array or a table with rows and columns.\

**NumPy arrays have one dtype for the entire array while pandas DataFrames have one dtype per column.**  

Selection by label - loc\
Selection by position - iloc\

Merge example - pd.merge(left, right, on="key")\

GroupBy example - df.groupby("A")[["C", "D"]].sum()  

A Parquet file (.parquet) is an open-source, column-oriented binary file format designed for highly efficient data storage and retrieval, particularly for big data analytics.  

Pivot Tables Advantage - Handle Big Data, automate repetitive reports, clean data, run statistics, and draw charts in the same place


