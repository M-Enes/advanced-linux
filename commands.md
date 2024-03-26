    cal
    -> Shows calendar


    cat <file_name>
    -> Shows file content


    cd <folder>
    -> Changes directory
    Folders:
    ~        -> user's directory
    ~myuser  -> myuser's directory
    .        -> current directory
    ..       -> parent directory


    clear
    -> Clears current terminal screen


    cp <source> <target>
    -> Copies the file
    cp -R <source> <target>
    -> Copies the directory


    date
    -> Shows system time


    echo <string>
    -> Prints string

    echo <string> > <file_name>
    -> Write string in file (no check for content, overwrites it)

    echo <string> >> <file_name>
    -> Appends string to file content


    find <directory> <find_commands>
-> Search for files in a directory hierarchy

    find <directory> -name <file_name>
-> Search for file in a directory hierarchy

    find <directoy> -user <user_name>
-> Search for user's files in a directory


    grep <search_string> <file_name>
    -> Search in file


    less <file_name>
    -> Shows file content with moving features


    ls
    -> Lists content of working directory
    Options:
    -l          -> long list
    -a          -> shows hidden content


    man <command>
    -> man command is used for information about commands.


    mkdir <directory_name>
    -> Makes a directory with given name


    mv <source> <target>
    -> Moves the file or directory


    nano
    -> nano is a command line text editor


    pwd
    -> Prints working directory


    rmdir <directory_name>
    -> Removes the directory


    rm <file_name>
    -> Removes the file
    rm -f <file_name>
    -> Removes the file forcely
    rm -i <file_name>
    -> Asks for removing file
    rm -r <file_name>
    -> Remove with child directories (recursive)


    touch <file_name>
    -> Creates a blank file


    uname
    -> Shows the operating system name
    uname -a
    -> Shows the detailed operating system information (eg. distribution, kernel version)


