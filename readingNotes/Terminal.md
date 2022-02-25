# Summarization for Terminal:
## The Command Line
 ### What is the Command Line:
 is the system's text-based user interface. You can enter commands by typing them on the keyboard, and you'll get feedback in the same way that text does.
 ### How do I get to one:
 Reading from [this](https://ryanstutorials.net/linuxtutorial/commandline.php)

 >Opening a terminal is fairly easy. I can't tell you exactly how to do it as every system is different but here are a few places to start looking.
If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.
If on Linux then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'.
If you are on Windows and intend to remotely log into another machine then you will need an SSH client. A rather good one is Putty (free) . 

## The Basic Navigation
- **Print Working Directory (pwd)**:this command  to remind what is your path current or present working directory {where your location are}.
- **list (ls)**:this command It show what's inside the directory {the contents of items}
- **Change Directories (cd)**:this command to move path to another directory.
- **Path** is a means to get to a particular file or directory on the system.

  - two types of paths:

       1- Absolute path 
  
       2- Relative path<br> 
       
       The difference between them is that absolute path always begin with a slash (/)
So When you refer to a file or directory on the command line you are actually referring to a path. The path can be constructed using any elements.
 
## More About Files
1- Everything is a file Under the hood, everything is actually a file. Even your keyboard is a file (one that the system reads from only) and your monitor is a File. This won't affect what we do too much but it will help understanding how the system works.<br>
2-A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is. The following are common extensions:
   - file.exe : an executable file, or program.
   - file.txt : a plain text file.
   - file.png, file.gif, file.jpg : an image.


In systems like Windows the extension is important and the system uses it to determine what type of file it is. Under Linux the system ignores the extension and looks inside the file to determine a file's type. Luckily there is a command called file which we can use to find this out.
When we specify a file or directory on the command line it is actually a path. It means to get to a particular location in the system and that location is a file. directories (as mentioned above) are just a special.<br> 

3- Linux is Case Sensitive
In Linux it is possible to have two or more files and directories with the same name but letters of different case. This can cause problems for people new to the operating system as they don't use the same characters for different parts of the computer system at the same time. 
A common mistake is to see an option which is upper case but enter it as lower case so be aware of case sensitivity when dealing with command line options.

4- Spaces in names
A space on the command line is how we separate items. Spaces in file and directory names are perfectly valid but we need to be a little careful with them.
E.g. Holiday Photos in the example we saw is seen as two command line arguments. To get around this we need to identify to the terminal that we wish Holiday Photos to be seen as a single command line argument. There are two ways for this:<br>
•	Quotes: either using single or double quotes anything inside quotes is considered a single item.<br>
•	Escape Characters: It is a backslash ( \ ). It escapes (or nullify) the special meaning of the next character.<br>
5-Hidden Files and Directories
Linux allows you to specify whether or not a file or directory is hidden. If the file's name begins with a. (full stop) then it is considered to be hidden. You can also rename a hidden file to remove the dot and it will become unhidden.
## Manual Pages
The Linux command line offers a wealth of power and opportunity.

1-Manual Pages So what are they exactly? They are a collection of pages that describe each command on the system

2-Searching: On the Manual pages, you may perform a keyword search. This is useful if you're not sure which command to use but know what you want to do. If the phrase occurs more than once, hit the 'n' key to cycle between them and to search for a manual page u use a forward slash

## File Manipulation
mkdir Create a directory, i.e. Make a directory for your files. rmdir Delete the directory - i.e. Remove a directory from the system. touch Make a new blank file. cp Copy (i.e. a copy of a copy of a copy of a copy A file or directory is copied. mv Make a move -i.e. Change the location of a file or directory (can also be used to rename). rm Delete - i.e. Remove a file from your computer.


## Cheat Sheet
 It includes the majority of the most important commands, as well as instructions on how to use them.

[Cheat Sheet page](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)