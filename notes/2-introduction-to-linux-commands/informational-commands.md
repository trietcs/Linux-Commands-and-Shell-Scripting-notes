# Informational Commmands
## User information
* Display user information
* Verify indentity or identify user account
* `whoami` - displays the current user's username
  > The `whoami` command takes no arguments and has no options.
* `id` - returns the user or group ID
  > using `id` with `-u` option "`id -u`" returns the numerical ID of user. If would like the name corresponding to the numerical user ID, add the `-n` option "`id -u -n`"

<img src="/images/user_information_1.png" alt="Example Image" width=400>

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
<img src="/images/system_information.png" alt="Example Image" width=600>
