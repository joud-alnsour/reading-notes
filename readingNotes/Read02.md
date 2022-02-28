# In Tests We Trust - TDD with Python
## What are Unit tests?
 Are a training or workout for your code(input, output, and behavior). and You are free to write them whenever you want.
## what is TDD ?
Test-Driven Development (TDD) is a methodology that prioritizes thinking about (and writing!) tests.<br><br>
**The First Step of TDD is:** <br>
- What is the simplest test we can run on a function?

   Example : 
> def test_should_return_female_when_the_name_is_from_female_gender():<br>
    detector = GenderDetector() <br>
    expected_gender = detector.run(‘Ana’)<br>
    assert expected_gender == ‘female’

- The name of the test file should be the same as the module name.
Example : if our module is **gender.py**, our test name should be **test_gender.py**
- Other thing to care about is the structure. A convention widely used is the 3A: (Arrange, Act and Assert)

    - Arrange: You'll need to organize the data you'll require to run that code (input).
    - Act: this is where you'll run the code that's being tested.
    - Assert: after running the code, check to see if the result (output) matches what you expected.
      
      
## The Cycle:
>The Cycle is made up by three steps:<br>
    a. 🆘 Write a unit test and make it fail (it needs to fail because the feature isn’t there, right? If this test passes, call the Ghostbusters, really)<br>
    b. ✅ Write the feature and make the test pass! (you can dance after that)<br>
    c. 🔵 Refactor the code — the first version doesn’t need to be the beautiful one (don’t be shy)
    **Using baby steps you can go through this cycle every time you add or modify a new feature in your code.**

 [Page Link](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)
  

# What does the if __name__ == “__main__”: do?
- in python, import the function on the required file... but during testing, the function will execute even if it is not called on the required file, therefore to avoid this, we use if __name__ == “__main__”  ;

- What this means is that if indent lines are called from other files, they will not run.<br>

**Advantages:**

>1- Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.<br>
2- If you import this script as a module in another script, the __name__ is set to the name of the script/module.<br>
3- Python files can act as either reusable modules, or as standalone programs.<br>
4- if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.

[Page Link](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)

# Recursion   
## What is Recursion? 
  is the process of a function calling itself directly or indirectly, and the associated function is known as a recursive function.
> What is base condition in recursion? <br>
In the recursive program, the solution to the base case is provided and the solution of the bigger problem is expressed in terms of smaller problems.  

[Page Link](https://www.geeksforgeeks.org/recursion/)

# PyTest 
## What is PyTest?
 is a testing framework that lets users build test scripts in Python. It aids in the creation of easy and scalable test cases for databases, APIs, and user interfaces. 

**pytest has a number of advantages:**
- Because of its basic and straightforward syntax, it's a breeze to get started with.
- Tests can be run in parallel.
- Can execute a single test or a group of tests.
- Automatically detect tests.
- Tests can be skipped.
- Source code is freely available.

[Page Link](https://www.guru99.com/pytest-tutorial.html)

