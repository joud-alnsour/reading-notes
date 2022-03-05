# Classes and objects
- Objects are a collection of variables and functions that are encapsulated into a single entity. Classes provide variables and functions to objects. Classes serve as a starting point for creating your items.
- A recursive function will keep calling itself and repeating its action until some condition is met, at which point it will produce a result.
All recursive functions have a two-part structure: the base case and the recursive case.
- Each recursive call adds a stack frame to the call stack (with its execution context) until we reach the base case. As each call delivers its results, the stack begins to unravel.
- Because each recursive call has its own execution environment, state must be maintained during recursion in one of two ways:

   - Through each recursive call, thread the state such that it is part of the current call's execution context.   

   - Maintain the state's global breadth



  [Page Link]( https://www.learnpython.org/en/Classes_and_Objects)

  
# Thinking Recursively
Recursive data structures in Python A recursive data structure is one that is defined by calling itself:<br>
1-Lists<br>
2-sets<br>
3-dictionaries<br>
4-trees<br>
[Page Link](https://realpython.com/python-thinking-recursively/)

# Pytest Fixtures and Coverage
- Fixtures are defined in pytest by combining the pytest.fixture decorator with a function definition.
- coverage: it will become more difficult to eyeball software as it becomes larger and more complicated. That's where "code coverage" comes in, ensuring that your tests have ran all of the code.
-Fixtures: A fixture gives the tests a specified, repeatable, and consistent context.

- **How can you use pytest to provide code coverage?**<br> It turns out that you can download and install a package named pytest-cov from PyPI. After that, you may use the --cov option to run pytest.<br>

[Page Link](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)

 