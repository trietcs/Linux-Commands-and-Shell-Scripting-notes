# Overview of the Linux shell
The **shell** is an OS-level application that interprets commands.

Use command to:
* Move and copy files
* Write to and read from files
* Extract and filter data
* Search for data
  
Shell versions:
* Bash
* Zsh

# Overview of a Linux terminal
The **terminal** is an application you use to interact with the shell.

Enter commands and recieve output from them.

![](/images/example-terminal.png)
For example, to start the Python application and run a program called ”myprogram.py", type `python myprogram.py`. When you press `Enter`, the shell runs the command. This program prints the words “Hello, World!” to the terminal. 

## Communicating with Linux system
_**How are commands run?**_
![](/images/communicating-with-linnux-system.png)
First, we have a **user** who wants to run a **command**. They enter the command in a **terminal**, which is then relayed to the **shell**. The core components of the **OS and kernel** translate the command for the **hardware** to perform. When the **hardware** completes the command, the kernel reads any changes or results and sends them back via the shell to the terminal for the user’s information.

The terminal is a powerful way to run applications and interact with your machine.

## Paths in the Linux filesystem
The filesystem is the human-readable directory or file location `/home/me/Documents/`

`a/b` indicates the file or directory named _b_ inside the directory named _b_

Special paths:
* `~` Home directory
* `/` Root directory
* `..` Parent of current directory
* `.` Current directory

> [!NOTE]
> Typing and entering `ls` will display all files and directories contained within your current working directory.
> 
> If you know the path to a directory, you can view its contents by passing the path name as a command line argument to the `ls` command as follows: `ls [PATH TO DIRECTORY]` eg: `ls /`, `ls /bin`
>
> The `pwd` command prints the path name to the present working directory

## Tab Completion
Many shells support a feature called **tab completion**.
Tab completion allows you to autocomplete a command you're typing on the command line.

Suppose you're in your home directory `~`, which contains the directories:

* `Pictures`
* `Videos`
* `Documents`
* `Downloads`

> [!NOTE]
> If you type: `~ $ cd Doc` and press `Tab`, the shell will autocomplete to: `~ $ cd Documents/`

## Command History
> [!TIP]
> You can navigate previous commands you've entered using the `Up Arrow` and `Down Arrow` keys.
