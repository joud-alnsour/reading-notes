# List Comprehensions
- List comprehension is a strong and concise Python method for constructing lists that becomes increasingly important as you work with lists and lists of lists.

- For example,my_new_list = [ expression for item in list ]  three items are required for list comprehension.
   - First is the expression we want to use. inside the square brackets expression.
   - Second parameter is the object on which the expression will operate. object enclosed in square brackets.
   - Third, we'll need an iterable list of objects from which to construct our new list. Inside the square brackets, make a list.
- When you perform an expression on each item in a list, the expression determines which item is saved in the output list.

- You can compress a list with a single line of code or add conditional statements in the form of filters to improve the precision with which lists are handled.

- List comprehension methods are a sophisticated approach of creating and managing lists.

- List comprehensions are a more concise approach of generating lists in Python.

- List comprehension is more versatile than loops and is usually faster than other methods.

- Before List comprehensions: squares = [] for x in range(10): squares.append(x**2) print(squares) output: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]

- With List Comprehensions: squares = [x**2 for x in range(10)] print(squares) output: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]

- Multipy by 3 with list comprehension: multiples_of_three = [ x*3 for x in range(10) ]

- List Comprehensions with filter for even numbers: even_numbers = [ x for x in range(1,20) if x % 2 == 0]

- List Comprehensions to find the first letter in a list: letters = [ name[0] for name in authors ]

- List Comprehensions to separate the letters in a string: letters = [ letter for letter in "20,000 Leagues Under The Sea"]

- List Comprehensions with a built in method: lower_case = [ letter.lower() for letter in ['A','B','C'] ] upper_case = [ letter.upper() for letter in ['a','b','c'] ]

- List Comprehensions to read each line in a file: poem = [ line for line in file ]

- list comprehension with user function followed by filter No Filter: def double(x): return x*2 nums = [double(x) for x in range(1,10)] Output: [2, 4, 6, 8, 10, 12, 14, 16, 18]

- With Filter: even_nums = [double(x) for x in range(1,10) if x%2 == 0] Output: [4, 8, 12, 16]

- List Comprehension with additional arguments: nums = [x+y for x in [1,2,3] for y in [10,20,30]] Output: [11, 21, 31, 12, 22, 32, 13, 23, 33]

[Page Link](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)

