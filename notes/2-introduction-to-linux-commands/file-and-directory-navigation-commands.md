# File and Directory Navigation Commands
## Listing your directory contetns
`ls` (list) - list files and directories

To list the contents of a specific folder using `ls <specific-name`, example `ls Downloads`
<img src="/images/ls_1.png" width=600>

The `ls` command also supports options that will list additional information.
* `-l` option, which will show child files and directories in a longer, more detailed format.
<img src="/images/ls_2.png" width=600>

## Finding your working directory
`pwd` (print working direcotry) - get current working directory
<img src="/images/pwd.png" width=600>

Here you can see that you're currently working in your home directory `Users/me`

## Navigating your directories
`cd` (change directory) - change the directory you are working in
<img src="/images/cd_1.png" width=600>

The `cd` command enables to change directories with either a relative or an absolute path.
* To get to the parent directory relative to your current folder, enter:
  ```
  cd ..
  ```
* To navigate directly to home folder, enter:
  ```
  cd ~
  ```
* You can also provide a full path to a directory, example:
  ```
  cd /Users/me/Documents/Academics/Math/Notes
  ```
<img src="/images/cd_2.png" width=600>

## Finding files
`find` - find files in directory tree
<img src="/images/find.png" width=600>

Let’s say you’re working in your `Documents` folder and want to find the paths of all files named `a.txt` within your working directory. To do so, type `find . -name "a.txt"`.” The `.` argument means **search within here**, so the command will only search within your current working directory.

To perform a case-insensitive version of your search, you can use the `-iname` option instead. You’ll see that you find the same file, plus another file with the same name but with an uppercase `A`.
