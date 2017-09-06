# Command line cheat sheet

This is my command line cheat sheet. I can refer to this document in the future if I forget a specific command in the future.

## Overview
* [cat](#cat)
* [cd](#cd)
* [cp](#cp)
* [echo](#echo)
* [grep](#grep)
* [less](#less)
* [ls](#ls)
* [mkdir](#mkdir)
* [mv](#mv)
* [nano](#nano)
* [pwd](#pwd)
* [rm](#rm)
* [sed](#sed)
* [sort]($sort)
* [tail](#tail)
* [>](#>)
* [>>](#>)
* [|](#|)


## Commands
### cat
* Example
  * `$ cat hello.txt`
* Description
  * This command outputs the content of a file into the termianl (standard output)
### cd
* Example
  * `$ cd nameofdirectory`
* Description
  * This command changes the current directory. Adding ".." moves you up one directory.
### cp
* Example
  * `$ cd file1.txt file2.txt`
* Description
  * This command copies the contents of a file/directory (first args) to another (last arg)
### echo
* Example
  * `echo hello`
* Description
  * This command accepts a standard input (through terminal) string and outputs a standard output (outputted terminal info)
### grep
* Example
  * `grep Mount mountains.txt`
* Description
  * This command is short for Global Regular Expression Print.
  * It searches for lines that match a pattern and returns the results.
* Options
  * -i is used to make the command non case sensitive.
  * -R is used to make the command recursive, so that it searches through the children as well
  * -l is used to make the command output the filenames of of the files with matches, instead of just the lines.
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
  * This command files or directories from one place to another. 
  * Last argument is the destination.
### nano
* Example
 * `$ nano`
* Description
 * Built in text editor for terminal.
### pwd
* Example
  * `$ pwd`
* Description
  * This command Prints the Working Directory (hence pwd), showing what directory you are in.
### rm
* Example
  * `$ rm`
* Description
  * This command is used to remove files or directories, permanently.
* Options
  * -r stands for recursive, and is used to murder a directory and all its children.
### sed
* Example
  * `$ sed 's/snow/rain/g' forests.txt`
* Description
  * This command stands for Stream EDitor. 
  * It accepts standard input and modifies it using an expression, before outputing it, like search and replace.
* Expression Breakdown
  * s stands for substiution. It is always used when substituting.
  * snow is the search string.
  * rain is the replacement string.
  * g stands for global, it means all isntances of snow will be replaced. Without it, only the first instance of snow per line would get replaced.
### sort
* Example
  * `$ sort nameoffile.txt`
* Description
  * This command takes in standard input and provides standard output, with the output being sorted alphabetically.
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
### uniq
* Example
  * `uniq deserts.txt`
* Description
  * Takes in input, and outputs data with identical, adjacent lines filtered out.
### >
* Example
  * `$ echo "hello" > hello.txt`
* Description
  * This command redirects output as input.
  * The redirect command in this case redirects the standard output of echo into a file.
  * When written in the other direction, it performs the same function, just the input and output are switched.
  * Used to pass output to a file or stream.
### >>
* Example
  * `$ cat mountains.txt >> clouds.txt`
* Description
  * This command redirects standard output, but has it be appended to the destination, intstead of replacing it.
   * Essentially just an extension of the ">" command.
### |
* Example
  * `$ cat volcanoes | wc | cat > islands.txt`
* Description
  * Used to pass output to a program or utility.
    
