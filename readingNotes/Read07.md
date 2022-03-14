# Python Scope
The concept of scope governs how variables and identifiers in your code are looked up. It determines whether or not a variable is visible in the code. The scope of a name or variable is determined by the location in your code where it is created. A rule known as the LEGB rule is commonly used to demonstrate the Python scope idea.<br>

Local, Enclosing, Global, and Built-in scopes are represented by the letters LEGB in the acronym LEGB. This diagram depicts not only the Python scope levels, but also the steps Python takes to resolve names in a program.<br>

**Understanding Scope**<br>
The scope of a name in programming refers to the area of a program where you can explicitly access that name, such as variables, functions, and objects. Only the code in its scope will see and be able to access a name. Scope is used in several programming languages to avoid name collisions and unpredictable behavior.<br> The most typical distinction is between two general scopes:
- Global scope: All of your code can use the names you define in this scope.
- Local scope: The names you declare in this scope are only available to or visible to the code that is contained within it.

**Namespace vs. Scope in Python**<br>
The concept of scope is strongly tied to the concept of namespace in Python. A Python scope, Python scopes work as dictionaries, mapping names to objects. Namespaces are the common name for these dictionaries. These are the specific mechanisms Python employs for storing names. They're saved in .__dict__. , a special attribute.<br>
The namespace of a module stores the names at the top level of the module. In other words, they're saved in the.__dict__  attribute of the module.<br>
**Using the LEGB Rule for Python Scope**<br>
The LEGB rule, named after the Python scope for names, is used to resolve names in Python. Local, Enclosing, Global, and Built-in are the letters in LEGB.
- Local (or function) scope: