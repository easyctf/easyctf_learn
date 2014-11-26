## pwd

### Print Working Directory
The current working directory is the directory you are currently working in in your shell.

This command is used for:

* Finding the full path to the current directory
* Storing the full path of the current directory into a shell variable

To print the current directory:

    pwd
    
To store the path into a variable:

    var = $(pwd)
    echo "The current working directory is $var"