# FileIO & Exceptions
**What Is File**<br>
A file is a collection of bytes used to store information. This information is structured in a specified format, which might range from a basic text file to a complex program executable.<br>

**Parts of the files :-**
- Header : Include The MetaData  which contains information about the file. 
- Data: The file's contents.
- End Of File: a special character that denotes the file's end.

**Paths to Files**<br>
The File Path is a String that represents the file's location in the operating system.

**Path Parts**
- Folder Path 
- File Name
- File Extension

**Opening and Closing a File in Python**
To Open a file in python we use the `open()` method that take a one parameter which is a file path

We have two options for closing the file:<br>
- **The First One**using try-finally

- **The second way** using with statment


## three distinct types of file objects:
- Text files
- Buffered binary files
- Raw binary files

**Reading and Writing Opened Files**<br>
 Reading we can read from the file using three method 
  - read()
  - readline()
  - readlines()
  

   
[Page Link](https://realpython.com/read-write-files-python/)

## Python Exceptions

**Exceptions versus Syntax Errors**<br>
When the parser identifies an erroneous statement, syntax errors occur. Where there is an exception error When syntactically correct Python code produces an error, this is the type of mistake that occurs.

> print( 0 / 0 ))<br>
  File "<stdin>", line 1
    print( 0 / 0 ))
                  ^
SyntaxError: invalid syntax


**The try and except Block: Handling Exceptions**<br>
Exceptions are caught and handled in Python using the try and except block.


>try:<br>
    linux_interaction()<br>
except:<br>
    pass
    
**Cleaning Up After Using finally**<br>
Consider how you'd have to build some type of cleanup mechanism every time you ran your code. The finally clause in Python allows you to achieve this.<br>
[Page Link](https://realpython.com/python-exceptions/)