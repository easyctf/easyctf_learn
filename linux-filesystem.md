# File System

The file system in Linux is very similar to the one you are familiar with in Windows or in Mac. There is a hierarchy of folders and inside folders you can have files. We can also refer to folders as *directories*.

## Special Directories

### Root Directory

The root directory is `/`. This directory is at the top of the hierarchy of directories.

### Home Directory

Your home directory is `~`. This directory may vary depending on your system, but in EasyCTF, your home directory will be `/home/youruser`, where `youruser` is your username.

## Change Directory

To change a directory, type `cd` and the name of the directory you want to go to. Unless you start your path with `/`, this will always be relative. For example, examine the following system:

    /
        home
            folder1
                folder2
                    file3.txt
                file2.txt
            file1.txt
            (other folders and files)
        (other folders and files)
        
Suppose your current directory is `folder1`. You may see a prompt like this:

```bash
user@easyctf:~/folder1$ _
```
    
### Moving Down

To move down from `folder1` to `folder2`, simply type `cd folder2`. That's because `folder2` is inside of `folder1` right now and you can refer to it using a relative path. If you were in your home folder, you would not be able to refer to `folder2`, because `folder2` doesn't exist inside `~`. All you can see from `~` is `folder1` and `file1.txt`.

```bash
user@easyctf:~/folder1$ cd folder2
user@easyctf:~/folder1/folder2$ _
```

### Moving Up

Moving up is simple. In every directory (even empty ones), there are two hidden files: `.`, which refers to the current folder, and `..`, which refers to the parent folder. Basically, to move to the parent folder (like from `folder1` to `~`), just type `cd ..`




