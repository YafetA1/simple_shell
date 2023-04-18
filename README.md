ALX Simple Shell Team Project

General
Who designed and implemented the original Unix operating system
Who wrote the first version of the UNIX shell
Who invented the B programming language (the direct predecessor to the C programming language)
Who is Ken Thompson
How does a shell work
What is a pid and a ppid
How to manipulate the environment of the current process
What is the difference between a function and a system call
How to create processes
What are the three prototypes of main
How does the shell use the PATH to find the programs
How to execute another program with the execve system call
How to suspend the execution of a process until one of its children terminates
What is EOF / “end-of-file”?

Features 

Display a prompt and wait for the user to type a command.
The prompt is displayed again each time a command has been executed.
If an executable cannot be found, print an error message and display the prompt again.
Handle errors.
Handle command lines with arguments
Handle the PATH
exit built-in, that exits the shell
env built-in, that prints the current environment
read many chars at once and call the least possible the read system call
handle arguments for the built-in exit
Handle the commands separator ;
Handle the && and || shell logical operators
Handle variables replacement
Handle the $? variable
Handle the $$ variable
Handle comments (#)

