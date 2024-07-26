# advanced-linux
Repository for advanced linux knowledge such as important commands, files etc.

## Commands

### cal
Shows calendar

### cat *file_name*
Shows file content

### cd *folder*
Changes directory

Quick Folders:
* ~ user's directory
* ~ myuser myuser's directory
* . current directory
* .. parent directory

### clear
Clears current terminal screen

### cp *source* *target*
Copies the file

### cp -R *source* *target*
Copies the directory

### date
Shows system time

### echo *string*
Prints string

### echo *string* > *file_name*
Write string in file (no check for content, overwrites it)

### echo *string* >> *file_name*
Appends string to file content

### find *directory*
Search for files in a directory hierarchy

### find *directory* -name *file_name*
Search for file in a directory hierarchy

### find *directoy* -user *user_name*
Search for user's files in a directory

### grep *search_string* *file_name*
Search in file

### less *file_name*
Shows file content with moving features

### ls
Lists content of working directory

Options:
* -l long list
* -a shows hidden content

### man *command*
man command is used for information about commands.

### mkdir *directory_name*
Makes a directory with given name

### mv *source* *target*
Moves the file or directory

### nano
nano is a command line text editor

### pwd
Prints working directory

### rmdir *directory_name*
Removes the directory

### rm *file_name*
Removes the file

### rm -f *file_name*
Removes the file forcely

### rm -i *file_name*
Asks for removing file

### rm -r *file_name*
Remove with child directories (recursive)

### touch *file_name*
Creates a blank file

### uname
Shows the operating system name

### uname -a
Shows the detailed operating system information (eg. distribution, kernel version)

## Operators

```command1 | command2```\
Executes command1 then executes command2 with command1's output

```command1 > file_name```\
Writes command1's output (stdout) into file_name (no check, overwrites it)

```command1 >> file_name```\
Appends command1's output (stdout) into file_name

```command1 2> file_name```\
Writes command1's error output (stderr) into file_name

```command1 2>&1```\
Writes command1's error output (stderr) to stdout (prints on screen)

```command1 < file_name```\
Send file_name to command1 as input (stdin)

Command line stream codes:
* 0 : stdin
* 1 : stdout
* 2 : stderr

## Some Important Files

    /etc/resolv.conf           -> System DNS servers
    /etc/issue                 -> Distribution version
    /etc/passwd                -> Local users
    /etc/shadow                -> User password summaries
    /etc/sudoers               -> Sudo rules
    /home/*/.bash_history      -> User command history
    /home/*/.ssh/id*           -> SSH keys
    /home/*/.vnc               -> VNC remote access information

## Some Important Folders

    /      -> Root Directory
    /bin   -> User Binaries
    /sbin  -> System Binaries
    /etc   -> Configuration Files
    /dev   -> Device Files
    /proc  -> Process Information
    /var   -> Variable Files
    /tmp   -> Temporary Files
    /usr   -> User Programs
    /home  -> Home Directories
    /boot  -> Boot Loader Files
    /lib   -> System Libraries
    /opt   -> Optional add-on Apps
    /mnt   -> Mount Directory
    /media -> Removable Devices
    /srv   -> Service Data

## Compressing

### There are 3 different methods for compressing

> **compress** (extension .Z)  
compress - *compressing*  
uncompress - *uncompressing*

> **gzip** (extension .gz)  
gzip - *compressing*  
gunzip - *uncompressing*

> **bzip2** (extension .bz2)  
bzip2 - *compressing*  
bunzip2 - *uncompressing*

### Compressing with tar

#### Creating archives
`tar -zcvf archive.tar.gz file1 file2`  
Explaining parameters  
- -z for zip
- -c for create
- -v for verbose (graphical output)
- -f for file

#### Extracting archives
`tar -zxvf archive.tar.gz`  
-x parameter for extracting

#### Viewing files in archive
`tar -ztvf archive.tar.gz`  
-t parameter for list content

### Logs

```journalctl``` command can be used for log informations.

Additional information can be found on [journalctl manpage](https://man7.org/linux/man-pages/man1/journalctl.1.html).

## Also see
https://devhints.io/bash
