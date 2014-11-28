## Input/Output Redirection
### Standard Output
By default, most command line programs display results to the `standard output`, which directs its contents to the display.

If you want to redirect output to a file, you use the angle bracket `>`.

```bash
ls > file.txt
```

Basically what this does, is that what is usually displayed with `ls` isn't printed to the screen, instead the results are redirected and stored in a file called `file.txt`. You can redirect outputs of other commands too, but we are just using `ls` as an example.

If you call the command again, the file will be overwritten. So, if you want to add the results onto the end of `file.txt` instead of replacing what was there before, use two brackets `>>`:

```bash
ls >> file.txt
```

### Standard Input
By default, most command line programs accept input from the `standard input`, which is usually what you type in from the keyboard to a command.

To redirect input from a file instead of from the keyboard, you can use the angle bracket `<`.

```bash
sort < file1.txt
```

In this example, the `sort` command was used to sort the conents of `file1.txt`. The results of this were outputted on the display because the standard output was not redirected.

You can also combine redirecting outputs and inputs like this:

```bash
sort < file1.txt > sorted_file1.txt
```

It should be noted that the order you redirect the output and input doesn't matter.

### Pipelines
You can also connect multiple commands together with `pipelines`, which makes the standard output of one command be the standard input of another.

For example:

```bash
ls | less
```

This makes the contents of ls scroll instead of just printing the whole thing into the terminal at high speed.

