# simple_shell #
## PROJECT - ALX SOFTWARE ENGINEERING. ##

This is a simple shell project implemented in C programming language. A shell is a command-line interface that allows users to interact with the operating system by entering commands. This project aims to create a basic shell that can execute simple commands, handle input/output redirection, and support piping between commands.

### Compilation ###
compile the Shell program this way:
```
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
```

### Testing ###
Test the Shell this way in interactive mode
```
$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$
```
But also in non-interactive mode:
```
$ echo "/bin/ls" | ./hsh
hsh main.c shell.c test_ls_2
$
$ cat test_ls_2
/bin/ls
/bin/ls
$
$ cat test_ls_2 | ./hsh
hsh main.c shell.c test_ls_2
hsh main.c shell.c test_ls_2
$
```

Contributors:
Millan Ouma 
Khwezi Shiriken
