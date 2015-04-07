---
layout: post
title:  Bourne Shell Commands
date:   2015-03-26
categories: computers shell commands
---
The Bourne shell is a command line environment for Unix, Linux and other operating systems.

|*Command*|*Example*|*Description*|
|cat|$ cat test.txt|Display the contents of the file test.txt|
|cd|$ cd my_folder|To change directory to the folder my_folder|
||$ cd ~|To change to the logged in users home directory|
||$ cd ..|To change to the folder one level above the current folder|
||$ cd ../..|To change to the folder two level above the current folder|
|chmod||Change file permissions (read, write, execute etc.)|
|cp|$ cp ~/Desktop/code/HelloWorlds/build.sh|Copy the file build.sh to the current directory|
|echo||Display text or display environment variables|
||$ echo $PATH|Display the path for the shell|
||$ echo $CLASSPATH|Display path for Java classes|
|ls|$ ls|To list all files and folders in the current folder|
|mkdir|$ mkdir test|To create the folder test under the current folder|
|mv|$ mv test.txt my_folder|Move the file test.txt to the sub-folder|
|pwd|$ pwd|Show full path to the current working directory|
|rm|$ rm my_folder/test.txt|Remove the file test.txt from the sub-folder|

## Shortcuts: ##
- use the tab key to autocomplete locations and commands.
- . is the current folder, .. is the parent folder
- ~ is the users home folder

## References: ##
Andy Hunt.  Learn to program with Minecraft plugins.  2nd Edition.  Pragmatic Bookshelf.
[Chapter 1](http://my.safaribooksonline.com/book/programming/game-programming/9781680500523/learn-to-program-with-minecraft-plugins-2-edition/f_0012_html)