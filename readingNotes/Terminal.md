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
- Everything is actually a file.Even your keyboard and your monitor and directory is a File.<br>
- The extension have 2 - 4 characters , After a full stop indicate the type of file.
<br> The following are some examples of common extensions:
   - file.exe : an executable file, or program.
   - file.txt : a plain text file.
   - file.png, file.gif, file.jpg : an image.
<br>

- Hidden files are ones that begin with . therefore in order to see those files using ls, we must add the -a option to make it like ls -a. 

- To get out of the spaces, use tab completion.

## Manual Pages
The Linux command line offers a wealth of power and opportunity.

- Manual Pages So what are they exactly? They are a collection of pages that describe each command on the system.

- Searching: On the Manual pages, you may perform a keyword search. This is useful if you're not sure which command to use but know what you want to do. If the phrase occurs more than once, hit the 'n' key to cycle between them and to search for a manual page u use a forward slash.

## File Manipulation
mkdir Create a directory, i.e. Make a directory for your files. rmdir Delete the directory - i.e. Remove a directory from the system. touch Make a new blank file. cp Copy (i.e. a copy of a copy of a copy of a copy A file or directory is copied. mv Make a move -i.e. Change the location of a file or directory (can also be used to rename). rm Delete - i.e. Remove a file from your computer.


## Cheat Sheet
 It includes the majority of the most important commands, as well as instructions on how to use them.

[Cheat Sheet page](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)