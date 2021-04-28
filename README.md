# Linux Commands 
## Basic
- `sudo command`: run a command as an admin
- `sudo su`: move into admin mode
- `ls`: list directory
- `ll`: list dir with permisions
- `mkdir`: create a directory
- `pwd`: lets you know your current directory
- `nano filename`: opens filename using the nano editor. If the file doesn't exist, it's created
- `mv`: for moving files. Can also rename files using it
- `rm`: used to remove files
- `ps`: check processes that are running
- `man cmd`: Manual of the command
- `apt (install | remove)`: Package manager
- `mkdir`: Make folder
- `ls (-a) - list files,`: a shows all files
- `touch`: makefile
- `cd ..`: up a dir
- `cp`: copy
## Permissions
- `chmod (+rwx | -rwx)`: change permissions
  - `+ | -`: add or remove permission
  - `r`: read permission
  - `w`: write permission
  - `x`: execute permission
  - `777`: read, write and execute for everyone
  - `400`: same as 777 but only for the issuing user
  - `600`: same as 777 but only for the file owner and restricts all others
  - `top`: task manager
- `kill pid`: Kills a process based on its pid
- `sudo systemctl (status | start | stop | restart)`: Manage background services

## Wildcards:

`*`: All files
`.`: Current folder
`..`: Up one folder
`head`: prints first 10 lines of a file

`tail`: prints last 10 lines of a file

`sort`: sorts information in a file

`nl`: prints a file with numbered lines

`wc`: print out a word count

`cmd 1 | cmd 2`: Use command 1 and use that output as input for command 2

`cmd > file`: redirect output into a file and overwrite the contents

`cmd >> file`: redirect output into a file and append it to the end
