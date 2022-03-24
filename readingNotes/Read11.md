# JupyterLab
JupyterLab is a flexible, integrated, and expandable environment for working with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components.<br>

**Code Consoles:**<br>
Transient scratchpads are provided for interactively running programs, with complete support for rich output. As a computation log from the notebook, a code terminal can be coupled to a notebook kernel.<br>
**Kernel Backed documents:**<br>
Enable interactive execution of code in any text file (Markdown, Python, R, LaTeX, etc.) in any Jupyter kernel.

[Page Link](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html)


# Numpy
Numpy is a Python data analysis package that may be used to speed up workflow and communicate with other Python packages.

**Creating a Numpy array**
- Add the numpy package to your project.
- To transform the list of lists wines into a NumPy array, use the array function.
   - Use list slicing to remove the header row.
   - To ensure that each element is converted to a float, use the keyword argument dtype.

**NumPy to read files**
- Use the genfromtxt function to read in the winequality-red.csv file.
- Specify the keyword argument delimiter=";" so that the fields are parsed properly.
- Specify the keyword argument skip_header=1 so that the header row is skipped. <br>
```wines = np.genfromtxt("winequality-red.csv", delimiter=";", skip_header=1)```

**Several NumPy methods:**

numpy.ndarray.sum - Adds values in an array together.
numpy.ndarray.mean — finds the mean of an array.
numpy.ndarray.std — finds the standard deviation of an array.
numpy.ndarray.min — finds the minimum value in an array.
numpy.ndarray.max — finds the maximum value in an array.<br>

[Page Link 1](https://www.tutorialspoint.com/numpy/index.htm)<br>

[Page Link 2](https://www.dataquest.io/blog/numpy-tutorial-python/)
