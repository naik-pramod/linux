### Shell

Almost all Linux distributions supply a shell program from the GNU Project called bash.

`[me@linuxbox ~]$`

If the last character of the prompt is a hash mark (#) rather than a dollar sign, the terminal session has superuser privileges.
This means either we are logged in as the root user.

#### df
To see the current amount of free space on the disk drives.
`df`

#### free
To display the amount of free memory
`free`

#### exit
To exit the terminal
`exit`

#### pwd
Print name of current working directory
`pwd`

#### cd
Change directory
`cd`

#### ls 
List directory contents
`ls`

we can specify the directory to list.
`ls /usr`

We can also change the format of the output to reveal more detail. -l indicates long format
`ls -l`


a --all

List all files, even those with names that begin with a period, which are normally not listed (that is, hidden).

-A --almost-all

Like the -a option except it does not list . (current directory) and .. (parent directory).

-d --directory

Ordinarily, if a directory is specified, ls will list the contents of the directory, not the directory itself. Use this option in conjunction with the -l option to see details about the directory rather than its contents.

-F --classify

This option will append an indicator character to the end of each listed name. For example, it will append a forward slash (/) if the name is a directory.

-h --human-readable

In long format listings, display file sizes in human-readable format rather than in bytes.

-l 

Display results in long format.

-r --reverse

Display the results in reverse order. Normally, ls displays its results in ascending alphabetical order.

-S 

Sort results by file size.

-t 

Sort by modification time.

-rw-r--r--

Access rights to the file. The first character indicates the type of file. Among the different types, a leading dash means a regular file, while a d indicates a directory. The next three characters are the access rights for the file’s owner, the next three are for members of the file’s group, and the final three are for everyone else. Chapter 9 discusses the full meaning of this in more detail.