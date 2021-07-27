    command1 | command2
-> `Executes command1 then executes command2 with command1's output`

    command1 > file_name
-> `Writes command1's output (stdout) into file_name (no check, overwrites it)`

    command1 >> file_name
-> `Appends command1's output (stdout) into file_name`

    command1 2> file_name
-> `Writes command1's error output (stderr) into file_name`

    command1 2>&1
-> `Writes command1's error output (stderr) to stdout (prints on screen)`

    command1 < file_name
-> `Send file_name to command1 as input (stdin)`

    0: stdin
    1: stdout
    2: stderr
-> `Command line stream codes`
