# Simple-shell in C
![Linux no compilo](https://www.adslzone.net/app/uploads-adslzone.net/2020/05/Antivirus-para-Linux.jpg)
## What is a shell
It is the outermost layer of the operating system. Shells incorporate a programming language for controlling processes and files, as well as starting and controlling other programs.
### Compilator
`gcc 4.8.4 -Wall -Werror -Wextra -pedantic *.c -o shell`
### Run the shell
`./hsh`
## Example of how to launch the shell after compiling:
`./shell`
## Testing
Your shell should work like this in interactive mode:
~~~c
$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$
~~~
But also in non-interactive mode:
~~~c
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
~~~

## How to work a shell
The term shell is used to refer to those programs that provide a user interface to access the services of the operating system. These can be graphics or plain text, depending on the type of interface they use. Shells are designed to facilitate the way in which the various programs available on the computer are invoked or executed.

### there are two types of shell
1. Common text shells such as bash, emacs, Windows command prompt, among others.
2. Common graphical shells such as GNome, KDE, XFCE, LXDE, Unity, MacOS Desktop Environment, Windows Desktop, among others.
<hr>

### 1. pwd command
The pwd command stands for “print working directory” and is a simple but useful Linux command. This command is used to display the name of your current directory, which can be useful when browsing the file system.

Example

`pwd`
`/home/root`
<hr>

### 2. cd command
The pwd command stands for “print working directory” and is a simple but useful Linux command. This command is used to display the name of your current directory, which can be useful when browsing the file system.

Examples

`cd filename`
`cd .. `
<hr>

### 3. ls command
The ls command is a command line utility that lists the contents of a directory.
It is used to enumerate files and directories on Unix and Unix-like operating systems, including Linux.
The ls command can be used with the following parameters:
-l (long format list)
-a (list all files, including hidden ones)
-t (sort by last modified time)
-S (sort by file size)
Example

`ls -options file`
<hr>

### 4. cat command
Cat, although a simple command at its most basic level, is one of the most widely used Linux commands on the system. It stands for “to concatenate” and is used to show what is inside a text file. You can only use the cat command if you know the name and extension of the file you want to display.
Example

`cat file.extension`
<hr>

# AUTHORS:
`Kevin Munoz` kevinmunozb04@gmail.com
<br>
`Santiago Hinestroza`
hinestrozasantiago@gmail.com