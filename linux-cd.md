## cd
This command changes the shell's current working directory.

To use:

```bash    
cd [directory]
```    

For example:

```bash
cd documents/subfolder1/subfolder2
```

As you can see, directories are separated by `/`.

The `parent`, or the directory above the current one (in the example above the current would be `subfolder2` after changing to it, and the parent would be `subfolder1`) is represented by `..`.

So if you start in `documents/subfolder1/subfolder2`,

```bash
cd documents/subfolder1
```

and 

```bash
cd ..
```

are the same.

There is also a specially named directory that can be represented with a tilde `~`: the `home directory`. The `home directory` is the default directory that you're automatically placed into upon starting your shell. 

This means that if your username is `testuser` and your home directory is `home` these two will be equivalent:

```bash
    cd home\testuser
    cd ~
```    
   
    
Also, it should be noted that trailing slashes in directory paths are optional. Therefore, the following are the same:


```bash
    cd documents
    cd documents/
```    

    
    