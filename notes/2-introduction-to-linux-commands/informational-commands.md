# Informational Commmands
## User information
* Display user information
* Verify indentity or identify user account
* `whoami` - displays the current user's username
  > The `whoami` command takes no arguments and has no options.
* `id` - returns the user or group ID
  > using `id` with `-u` option "`id -u`" returns the numerical ID of user. If would like the name corresponding to the numerical user ID, add the `-n` option "`id -u -n`"

<img src="/images/user_information_1.png" alt="Example Image" height=300>

## System information
`uname` (Unix name) - returns OS information
> This can be used to identify the type of system you are working on or diagnose system-related issues.

To return the name of the OS, type:
```
uname
```
To return both the OS name and its version, using `-s` and `-r` options:
```
uname -s -r
```
To view more detailed version information, using `-v` option:
```
uname -v
```
<img src="/images/system_information.png" alt="Example Image" height=300>

## Displaying your disk usage
`df` (disk free) - Shows disk usage
> It useful in situations where you need to monitor disk usage or check the available space on a particular file system.

To see all the disks mounted on your home directory, type:
```
df -h ~
```
<img src="/images/df_1.png" alt="Example Image" height=300>

To view disk usage on all filesystems, type:
```
df -h
```
<img src="/images/df_2.png" alt="Example Image" height=300>

## Displaying current running processes
`ps` (process status) - Running processes
> This is helpful when you need to monitor or manage processes.

To list all processes running on the system, regardless of which user started them, type:
```
ps -e
```
<img src="/images/ps.png" alt="Example Image" height=300>

## Monitoring system health and status
`top` (table of processces) - Task manager
> Monitor system performance and resource usage

To show the top three running tasks, we use `-n` option and the number `3`:
```
top -n 3
```
<img src="/images/top.png" alt="Example Image" height=300>

> [!NOTE]
> `top` can provide many other details such as memory usage and the executable file location.

## Printing strings and variable values
`echo` - Display text or variables on the terminal or in a shell script.
<img src="/images/echo.png" alt="Example Image" height=300>
> [!NOTE]
> Additionally, you can view the value of a variable, such as our systme's `PATH` variable, by typing a `$` followed by the variable name.

## Viewing the manual
If you want to learn more about how to use a command, you can use the `man` (manual) command. 
<img src="/images/man.png" alt="Example Image" height=300>
> [!NOTE]
> All default Linux commands come with a manual that you can display using `man`.
