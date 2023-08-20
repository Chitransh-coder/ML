# Notes For NumPy and Pandas

These contain notes for NumPy and Pandas for Python.

---

## NumPy

NumPy is a Python library that provides functionality comparable to mathematical tools such as MATLAB and R. While NumPy significantly simplifies the user experience, it also offers comprehensive mathematical functions.

### NumPy Objects

1. **Arrays** are similar to lists in Python but they are completely optimised for numeric analysis. They can have multiple dimension so they are called ***ndarrays***. They also support slicing.

   - **Shape Attribute** : It helps in determining dimension of an array.
   - **Mean Function** : This function helps in determining the mean value of all the elements of an array.

---

## Pandas

Pandas is an extremely popular Python library for data analysis and manipulation. Pandas is like a spreadsheet application for Python—providing easy-to-use functionality for data tables.

## Pandas Objects

1. **Dataframe** are similar to SQL tables, they are used with NumPy to deal with 2D arrays.

   - **Loc Function** is the function used to locate data from specific index. You can use the loc method to find indexed rows based on a filtering expression that references named columns other than the index.
   - **ILoc Function** is used to retrieve data from its value.
    >**Loc vs ILoc**
    >**Loc** returns value from its index value whereas **ILoc** returns value from positions of the values.
    - **Query Function** is used to filter data based on its value and named references
    - **isnull Function** is used to find null or missing values in a dataframe.

### Loading Dataframe from a file

We can import data from a **CSV** *(comma-separated-values)* file using **read_csv()** function.
