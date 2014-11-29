# echo

Echo displays strings to standard output. The strings can be encased with either single or double quotes.

For example,

```bash
echo "Hello, EasyCTF!"
```
	
Outputs the following:

```
Hello, EasyCTF!
```
	
You can also declare variables and echo their values (note: to substitute values such as `$x`, you must use double quotes and not single quotes):

```bash
x = 15
echo "The value of x = $x"
```
	
Outputs:

```
The value of x = 15
```

If you want to print a new line or a tab use `\n` and `\t` and add the *option* `-e` (which allows backslash interpretation) and enclose the string(s) you want to print with double quotes.

There are also certain characters that won't be automatically printed such as `\`, `"`, etc. If you need to print these, you must `escape` them first, which means you need to precede them with another backslash (which tells the shell to ignore the next character). 


For example:

```bash
echo -e "this \\ is a backslash, \nthis \" is a double quote."
```

Outputs:

```
this \ is a backslash,
this " is a double quote.
```