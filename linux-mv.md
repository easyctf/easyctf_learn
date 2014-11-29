# mv
This command is used to move or rename files.

To rename files:

```bash
mv [option] [original file] [new file]
```

So if you are in the directory `documents` with the file `hello.txt`, to rename it to `newname.txt`:

```bash
mv hello.txt newname.txt
```

If you simply want to move without renaming (in this case move to the directory `music`:

```bash
mv hello.txt music/.
```

In this case, the period `.` means to place the file here without renaming it. You can also move and rename in the same step:

```bash
mv hello.txt music/newname.txt
```

## -i
If you are trying to rename a file to an existing name, this option causes the shell to prompt you for confirmation before overriding.



