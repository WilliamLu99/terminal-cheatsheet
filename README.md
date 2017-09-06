# Command line cheat sheet

This is my command line cheat sheet. I can refer to this document in the future if I forget a specific command in the future.

## Overview
* [cd](#cd)
* [less](#less)
* [ls](#ls)
* [mkdir](#mkdir)
* [mv]($mv)
* [pwd](#pwd)
* [tail](#tail)

## Commands
### cd
* Example
   * `$ cd nameofdirectory`
* Description
   * This command changes the current directory. Adding ".." moves you up one directory.
### less
* Example
  * `$ less nameoffile.txt`
* Description
  * This command is used to view but not edit the contents of a text file one screen at a time
### ls
* Example
  * `$ ls`
* Description
  * This command lists the files in the current working directory.
* Options
  * -a is used to list hidden files/folders (things prefixed with ".").
  * -l is used to list everything in a long format.
  * -t is used to list things by the time they were last modified.
### mkdir
* Example
  * `$ mkdir newdirectoryname`
* Description
  * This command creates a new directory.
### mv
* Example
  * `$ mv myfile ~/myfile`
* Description
This command files or directories from one place to another. 
### pwd
* Example
  * `$ pwd`
* Description
  * This command Prints the Working Directory (hence pwd), showing what directory you are in.
### tail
* Example
   * `$ tail nameoffile.txt`
* Description
   * This command displays the last portion of a file. It accepts optional arguments such as `-n` which allows you to indicate how many lines from the end of the file you'd like to display.
   
### touch
* Example
   * `$ touch keyboard.txt`
* Description
   * This command creates a new new empty file inside the current directory, taking the filename as an argument.
    
    
