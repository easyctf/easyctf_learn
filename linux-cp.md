## cp
This command copies files and directories.

To use:

    cp [original file name] [copied file name]
    
If you are in the current working directory `pictures/album1` and you want to copy the file `photo.jpg`:

    cp photo.jpg photo-2.jpg
    
Will create a copy of `photo.jpg` named `photo-2.jpg`

If the file you are trying to copy is in a different directory, say `documents/hello.txt` is the file you want to copy:

```bash
cp documents/hello.txt pictures/album1/hello-cp.txt
```

To copy multiple files, specify the files and have the last argument in the command be the directory the files will be copied into.

```bash
cp documents/test1.txt documents/test2.txt documents/test3.txt pictures/album1
```