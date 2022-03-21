# Dunder Methods
- special methods are a set of predefined methods that can be used to improve the functionality of your classes. Because they begin and conclude with double underscores, they're easy to spot.
- “dunder methods”, a short form of “double under"
- Dunder methods let you emulate the behavior of built-in types.
- The Python data model is an elegant design that allows developers to use advanced language capabilities such as sequences, iteration, operator overloading, attribute access, and more.
- Consider Python's data model as a sophisticated API with which you can interact by using one or more dunder methods.
- Object Initialization: init
   - I need a constructor to create account objects from a class, which in Python is the init dunder.
   - The constructor takes care of setting up the object
- Object Representation: str, repr
   - repr: An object's "official" string representation. This is how you would create a class object. Repr's goal is to be unambiguous.
   - str: An object's "informal" or nicely printable string representation. This is intended for the end user.
- The call dunder method can be used to make an object callable like a standard function.
- The context manager is a straightforward "protocol" (or interface) that your object must adhere to in order to be used with the with statement. If you want an object to act as a context manager, all you have to do is add enter and exit methods to it.<br>

**A set of Dunder methods is a collection of predefined methods. We can use them to mimic the behavior of built-in functions.**
- `__init__`: setting up the object
- `__str__`: nicely printed representation of an object
- `__repr__`: official string representation of an object
- `__len__`: makes a class iterable
- `__getitem__`: return certain items
- `__reversed__`: reverse the items in the class
- `__eq__`: compare values, return boolean
- `__lt__`: compare values, return boolean
- `__add__`: add values to the class
- `__call__`: use a print function while iterating through a class


[Page Link](https://dbader.org/blog/python-dunder-methods)


# Statistics - Probability
- A sample set of data is referred to as a trial.

- Mean and standard deviation are descriptive statistics.

- inferential statistics: a quick explanation of how the statistical result was arrived at.

- Statistics are the instruments used to test the theory of probability. Probability is the theory of outcome.

- A bell-shaped curve centered on the mean is known as a normal distribution.

**Central Limit Theorem & Three Sigma Rule**<br>
- In a normal distribution, 68 percent of observations fall within one standard deviation of the mean, 95 percent fall within two standard deviations, and 99.7% fall within the third standard deviation.

- The Z score indicates how far a data point deviates from the mean.

[Page Link](https://www.dataquest.io/blog/basic-statistics-in-python-probability/)