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
        
