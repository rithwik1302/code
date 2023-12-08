import os: A way to interact with the operating system, including file and directory operations.
'os.path.isfile('mtcars.csv')': This line uses the 'os.path.isfile()' function to check whether the specified path, in this case, 'mtcars.csv', points to a regular file. The function returns 'True' if the path refers to an existing regular file and 'False' otherwise.
print(...): The result of the 'os.path.isfile('mtcars.csv') '
'os.getcwd()': This line calls the 'getcwd()' function from the 'os' module. 'getcwd()' stands for "get current working directory," and it returns a string representing the current working directory.
print(...): The result of 'os.getcwd() '
The code 'import pandas as pd' is a common way to import the Pandas library in Python and assign it the alias 'pd'. 
The code 'data = pd.read_csv('mtcars.csv')' uses the Pandas library to read data from a CSV file named 'mtcars.csv' and store it in a Pandas DataFrame named 'data'.
entered just the variable name 'data'.it will display the contents of the Pandas DataFrame stored in the variable 'data'.
'data.info()' method in Pandas is used to display a concise summary of a DataFrame, including information about the DataFrame's columns, data types, non-null values, and memory usage. It provides a quick overview of the structure and properties of the DataFrame.
The code' data.plot('model', 'disp')' is used to create a basic line plot in a Jupyter notebook or another interactive Python environment. This code relies on the plotting functionality provided by the Pandas library.
The 'data.plot()' method is part of Pandas' built-in plotting functionality, which is a convenient way to create simple visualizations directly from a DataFrame.
The arguments 'model' and 'disp' specify which columns from the DataFrame should be used for the x-axis and y-axis, respectively. In this case, 'model' is likely treated as categorical data (on the x-axis), and 'disp' as numerical data (on the y-axis).
