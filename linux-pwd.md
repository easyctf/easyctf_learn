# pwd

pwd stands for "print working directory". The current working directory is the directory you are currently working in in your shell.

This command is used for:

* Finding the full path to the current directory
* Storing the full path of the current directory into a shell variable

To print the current directory:

```bash
pwd
```
    
To store the path into a variable:


```bash
var = $(pwd)
echo "The current working directory is $var"
```
