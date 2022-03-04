# Shell basics

The shell is a program that takes commands from the keyboard and gives them to the operating system to perform.
The bash is the default command-line shell for most Linux Distributions.

Every shell script starts with a shebang. This is a sequence of characters consisting of (#!)

This folder contains bash scripts that perform various tasks as listed below:

## Files in this folder

| File Name                   | Description                                                                                                                                                                                                                                                             |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [ 0-current_working_directory](0-current_working_directory) | a script that prints the absolute path name of the current working directory  |
|[  1-listit](1-listit)| a script that displays the contents list of your current directory  |
| [  2-bring_me_home](2-bring_me_home)| a script that changes the working directory to the user’s home directory. |
| [3-listfiles](3-listfiles)| a script that displays the current directory contents in a long format |
| [4-listmorefiles](4-listmorefiles)| a script that displays the current directory contents, including hidden files (starting with .) in the long format|
| [ 5-listfilesdigitonly](5-listfilesdigitonly)| a script that displays the current directory contents with the following conditions:Long format. With user and group IDs displayed numerically.And hidden files (starting with.)|
| [ 6-firstdirectory](6-firstdirectory)| a script that creates a directory named _my_first_directory_ in the _tmp/ directory_ |
|  [ 7-movethatfile](7-movethatfile)| a script that moves the file _betty_ from _/tmp/_ to _/tmp/*my_first_directory*|
|  [ 8-firstdelete](8-firstdelete)| a script that deletes the file _betty_.The file _betty_ is in _/tmp/my_first_directory_|
| [ 9-firstdirdeletion ](9-firstdirdeletion )| a script that deletes the directory _my_first_directory_ that is in the _/tmp_ directory.|
|  [ 10-back ](10-back )| a script that changes the working directory to the previous one. |
|  [ 11-lists ](11-lists )| a script that lists all files (even hidden) in the current directory and the parent of the working directory and the _/boot_ directory (in this order), in long format |
|  [ 12-file_type ](12-file_type )| a script that prints the type of the file named _iamafile_|
|  [ 13-symbolic_link ](13-symbolic_link )| a script that creates a symbolic link to* /bin/ls*, named _*ls*_. The symbolic link should be created in the current working directory |
|  [ 14-copy_html ](14-copy_html )| a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory |
|  [ 100-lets_move ](100-lets_move )| a script that moves all files beginning with an uppercase letter to the directory _/tmp/u |
|  [ 101-clean_emacs ](101-clean_emacs )| a script that deletes all files in the current working directory that end with the character ~.|
|   [ 102-tree ](102-tree )| a script that creates the directories _welcome/, welcome/to/ and welcome/to/school_ in the current directory |
|   [ 103-commas ](103-commas )| a script that writes a command that lists all the files and directories of the current directory, separated by commas (,)|
|  [ school.mgc ](school.mgc )| a script that creates a magic file _school.mgc_ that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0  |
