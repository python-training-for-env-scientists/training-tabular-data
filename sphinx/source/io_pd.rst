Reading and Writing Data with Pandas
======================================

# talk about how cool pandas read/write functionality is
# make a bunch of files that people can download and look at.. pass urls

Reading text files
--------------------
# start with read_csv
# showcase
    - header
    - names
    - index_col
    - skip_rows / nrows

# then explore read_table start with identical arguments as above, but a couple more useful ones
# showcase
    -sep
    -delim_whitespace

# explain that there are many more arguments for both of these functions

Reading from excel
--------------------

# simple example
# showcase
    - sheetname

Writing text files
---------------------

# just show to_csv

Other supported formats
-------------------------

# copy this table: https://pandas.pydata.org/pandas-docs/stable/io.html

Dataframe cleanup
-------------------
# rename, set_index, reset_index, dropping columns,