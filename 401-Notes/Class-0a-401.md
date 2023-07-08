# Practice in the Terminal

## The Command Line

- There must always be spaces between the command and the command line argument.  Options are usually listed before other arguments and start with a dash.
- The shell is a part of the OS that defines how the terminal will behave or look.  The most commone one is bash which stands for Bourne again shell.
- You can cycle back through previous commands by hitting the up arrow.

## Basic Navigation

- pwd: Print working directory
- ls: list (shows what is in our current location)
- File system is hierarchical.  There is a root directory followed by subdirectories denoted by a `/`
- Absolute paths specify a location in relation to root, relative specifies relative to current location.
- cd: change directory (use tab completion)

## More About Files

- Linux is case sensitive
- file[path] to find out file type.
- If there are spaces in file names, you need to enclose the name in quotes (single or double) in command line arguments.  Alternatively, you can use an escape character.
- ls -a to see all files in a directory including hidden files.

## Manual Pages

- The manual pages explain every command available in the system and how to use them.
- man \<command to look up>
- man -k \<search term> if you want to search the manual for keyword.

## File Manipulation

- mkdir[options]\<Directory>: Makes a new directory.
- rmdir [options]\<Directory>: Removes a directory.
- touch[options]\<filename>: Makes a new blank file.
- cp[options]\<source>\<destination>: Copies a file or directory.
- mv [options] \<source> \<destination>: Moves a file or directory.  We can also use this to rename things.
- rm [options] \<file>: Removes a file.

## Cheat Sheet

-[Link to Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
