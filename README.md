# SIMPLE SHELL #
## An ALX Software Engineering Project ##

This project involves creating a straightforward shell using the C programming language. A shell serves as a text-based interface enabling users to communicate with the operating system through commands. The goal of this project is to develop a basic shell capable of executing simple commands, managing input/output redirection, and facilitating piping between commands.

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
