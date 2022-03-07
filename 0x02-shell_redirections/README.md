# Shell Redirections 
The input/output redirection feature is used to redirect the output of commands to files, devices and even to the input of other commands.

### Standard output
This the facility where results from command line programs that display results are sent to.

To redirect standard output to a file, the ">" character is used. This character overwrites the contents of the file. 
In order to append new results, use the characters ">>"

### Standard input
This is a facility that accepts commands 
whose results come from the keyboard. The character "<" is used to redirect the standard output from a file.

Note: The redirection operators must appear after the other options and arguments in the command

### Pipelines
These are multiple commands connected together where the standard output of one command is fed into the standard input of another.

### Filters
A program that takes the standard input and performs an operation upon it then sends the result to the standard output. 
Programs that act as filters:

|Program | Function |
|--------|----------|
|sort|sorts standard input then outputs the sorted result on standard output.|
|uniq|removes duplicate lines of data |
|grep|examines each line of data it receives from standard input and outputs every line that contains a specified pattern of characters|
|fmt|reads text from standard input, then outputs formatted text on standard output.|
|pr|takes text input from standard input and splits the data into pages with page breaks, headers and footers in preparation for printing |
|head|outputs the first few lines of its input.|
|tail|outputs the last few lines of its input. |
|tr|translates characters.  |
|sed|stream editor. |
|awk|An entire programming language designed for constructing filters |
