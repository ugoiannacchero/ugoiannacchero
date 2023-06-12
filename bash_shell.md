Alma Linux9 Bash shell
=======================

## Table of contents:

- Basic stuff
- File Search and Text Manipulation
- SSH
- Git environment


# Basic stuff

`cd ..` allows you to move up one level in the directory hierarchy.

`ls` command is used to list the files and directories in the current working directory.

`cdls() { cd "$@" && ls; }` defines a function named "cdls" that combines the functionalities of both the "cd" and "ls" commands.

`touch` create an empty file, but it can also be used to modify the access and modification timestamps of existing files.

`mkdir` creates a new directory with the specified name in the current working directory. 

`mkdir folder1 folder2 folder3` is used to create multiple directories at once. 

`rmdir` removes **empty** directories or folders.

`rm` removes a **file**.

`rm -rf` forcefully and recursively delete directories and their contents (**warning!**)

`cp file1 file2` is used to copy the contents of one file (file1) to another file (file2).

`cp -r` is used to recursively copy directories and their contents.

`cp /home/asd/folder/{file{1,2},xyz,abc} /home/asd/dest` uses brace expansion in the shell to copy multiple files from a source directory to a destination directory.

`mv file1 file2` rename/move a file.

`pwd` will output the name of the present working directory.

`ln -s source_file symbolic_link` is used to create a symbolic link, also known as a soft link, between a source file and a symbolic link.

`type` determines the type and location of a command or program.
