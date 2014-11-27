## cat

The cat command is used for:

* Displaying a text file

		cat filename
	
  If you would like to display all files in the current directory, use the wildcard `*` like this:
  
		cat *
	
  To view all files or:
  
		cat *.txt
	
  To view all text files only.
	
* Reading a text file

  Sometimes a file will be too large to read since it won't fit on screen and will scroll by at high speed. To bypass this, use the `cat` command with `more` or `less`.
  
		cat bigfile | more
	
  or
  
		cat bigfile | less
	
* Creating a new text file

  To create a file named "test.txt":
  
		cat > test.txt
	
  Then, type the text you want to save into your file and press <kbd>Ctrl</kbd> + <kbd>D</kbd> when you are finished.
  
* File concatenation (adding files)

  To combine to files and create a new file called "newfile.txt":
  
	```bash
	cat file1.txt file2.txt > newfile.txt
	```
	
* Modifying files

  To add data to an existing file named "test.txt":
  
	```bash
	cat >> test.txt
	```
	
  Then type your text, and again, press <kbd>Ctrl</kbd> + <kbd>D</kbd> when finished.
