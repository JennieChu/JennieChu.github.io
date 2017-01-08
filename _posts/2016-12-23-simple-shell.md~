---
layout: post
title: Project - Holberton Simple Shell
---
![alt text](http://i.imgur.com/0l1v6rz.png"Holberton Simple Shell")


### Holberton Shell (hsh) is a simple command line shell for OS X and Linux. Hsh includes most basic features present in the bash shell. This shell was built as a project for Holberton School.

<br>
### <strong>Quick Start</strong>

------

HSH works like any other shell, like bash or zsh. Detailed user documentation on specific commands is available by running help within hsh.

HSH builds successfully with a GCC 4.8.5 compiler or later. HSH can compile using `gcc 4.8.4 -Wall -Werror -Wextra -pedantic *.c -o simple_shell`.

To start up HSH, simply type the following into your terminal:

```
./simple_shell
```

<br>

### <strong>Supported Features</strong>

------

#### <strong>1) Syntax</strong>

Like other shells, hsh is used by given it commands. Every hsh command follows the same general syntax: `command name {arguments}`. The command is executed by writing the name of the command followed by any arguments.

```bash
echo Hello Holberton
```

#### <strong>2) Commands</strong>

Any program in your computer can be used as a command in hsh. If the program is located in any of the directories in the PATH variable, then typing the filename is enough to run the command. Otherwise, a full path to the program is required.

<div style="margin-left: 1em;">
    <u>2.1 Command Seperation</u>
    <br>
    <br>
Commands and any arguments are seperated by a <code>' '</code>. Commands end with either a newline				  (i.e Return Key) or a<code>;</code>,<code>&&</code>, or <code>||</code>.<br>
    <br>
To enter more than one command in one line, a <code>;</code>can be used to seperate commands. Commands are read and executed left to right.
    <br>
    <br>
If commands are seperated by <code>&&</code>, the leftmost command is read and executed and if the execution failed, no other commands are executed, otherwise, the next command in line will be executed. If the commands is seperated by<code>||</code>, regardless of execution failure or success of the leftmost command, all suceeded commands are executed.
   <br>
   <br>
​   <u>2.2 Switches and Flags</u>
    <br>
    <br>
Switches and flags arguements of commands are also supported by hsh. Most switches start with a hypen,<code>-</code>and always somehows affect the command in one way.
	 <br>
	 <br>
​   <u>2.3 Comments</u>
    <br>
    <br>
hsh provides support for comments added into standard input. Comments can be inputed by placing a<code>#</code>before any statement. Comments are ignored by hsh.
</div>

#### <strong>3) Builtins</strong>
There are several builtins programmed into the hsh. Below is a description and use for each builtin.
<div style="margin-left: 1em;">
​     <u>3.1 Env, Setenv, Unsetenv</u>
      <br>
      <br>
To print out a list of all the environemental variables, the builtin `env` can be used. Each environmental variable and its value is printed out with a syntax of `key=value`. Each variable is seperated by a new line.
<br>
<br>
To set an environemental variable, the builtin is `setenv`. The syntax to use `setenv` is `setenv key value`. If one of the arguments is missing, an error is returned.
<br>
<br>
To remove an environemental variable, the builtin `unsetenv` can be used. The syntax to use `unsetenv` is `unsetenv key`. If no `key` value is given, an error is returned.
<br>
<br>
​	<u>3.2 cd</u>
<br>
<br>
The `cd` command changes the shell working directory. The syntax to use the command is `cd DIR`. If no `DIR` is given, it is defaulted to the HOME shell variable. The full path of the directory is needed. To change the directory to its parent, the argument `..` can be used.
<br>
<br>
​	<u>3.3 history</u>
<br>
<br>
To print out a list of previous commands used, the command `history` can be used. The previous 50 commands will be printed out. The history of all commands is written into the `.simple_shell_history` file.
<br>
<br>
​	<u>3.4 help</u>
<br>
<br>
To receive a description and the syntax use of a specific command, you can use the `help` command.
<br>
<br>
​	<u>3.5 exit</u>
<br>
<br>
To exit out of the shell, the user may use the `exit` builtin. To use `exit`, a status number, `n` can be given. If `n` is ommited, the exit status is that of the last command executed.
<br>
</div>
### <strong>Exiting commands and hsh</strong>
------
To exit out of a process or command, `ctrl c` is used. Control-C interrupts a process and causes it to abort.

To exit out of the hsh shell, the user can do one of the following, `ctrl D` or `exit n`. When exiting with `ctrl D`, an exit status of 0 is given. Using `exit`, you can input its exit status or it is defaulted to the status of the last command executed.
