# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

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

> > ctrl+left/right: moves between arguments in your command
> > !!: represents the last command you ran
> > cd -: move back to your last working directory
> > pwd: show current working directory path
> > mkdir: creating a directory
> > rm -r [directoryname]: deleting a directory (the -r deletes all child directories and files too)
> > touch [filename.txt]: create a .txt file
> > rm [filename]: deleting a file
> > mv [oldfilename] [newfilename]: renaming a file
> > mv [source directory] [new directory location]: moving a file
> > ls -a: list files starting with . (hidden files)
> > ls -t: list files in order of last modified
> > cp [source directory location] [new directory location]: copying a file from one directory to another

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

> > `ls`: lists the files in the working directory
> > `ls -a`: list all files including those starting with .
> > `ls -l`: list files in long format
> > `ls -lh`: list files in long format with readable file size
> > `ls -lah`: list all files including those starting with . in long format with readable file size
> > `ls -t`: list files in order of last modified
> > `ls -Glp`: list files in long format, adding / after each filename and coloring it blue if that file is a directory

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > `ls -d`: displays only directories
> > `ls -g`: long format but excludes owner name
> > `ls -R`: displays subdirectories as well
> > `ls -u`: display files by file access time
> > `ls -1`: display each entry on one line

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > `xargs` reads inputs from the user and executes the command. The default command is 'echo' (print the input).
> > You can use `xargs` to find files using the 'find' command and '-name' option. Each blank space is treated as a delimiter.
> > The delimiter can be changed when entering in `xargs`, with the '-d option'. E.g. xargs -d '\n' would only treat new lines
> > as a delimiter.
