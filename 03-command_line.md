# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > $ cd <directory> --change directory to <directory>
 $ pwd Display --path of current working directory
 $ cd .. --enter parent directory
 $ ls --list current directory contents
 $ ls -la --list detailed directory contents, including hidden files
 $ mkdir <directory> --Creat a new directory named <directory>
 $ touch <file> --creat a new file named <file>
 $ rm <file> --delete <file>
 $ rm -r <directory> --delete <directory>
 $ mv <file1> <file2> --rename <file1> to <file2>
 $ cp <file> <directory> -- copy <file> to <directory>

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > ls --list all files and directories in the current working directory
ls -a --list all contents, including hidden files and directories
ls -l --list all contents in the working directory in long format
ls -lh --list all contents in the working directory in long format and print sizes in human-readable format 
ls -lah --list all contents in human readable format, including hidden files
ls -t --order the files and directories by the time they were last modified
ls -Glp --list without group names


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -r, ls -u, ls -d, ls -f, ls -R

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs is used to build and execute commands from standard input. It converts input from standard input into arguments to a command.

 e.g : echo 'one two three' | xargs mkdir
