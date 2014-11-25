## Conditional Statements

### If, Else If, Else

If, Else If, and Else are conditional statements, meaning that the condition set by the statement decides which statement will be executed.

The format is usually as follows:

	if (condition1):
		code to be executed
	elif (condition2):
		different code to be executed
	{more elifs if needed}
	else:
		another different set of code to be executed

For example:

	for x in range(0,5):
		if (x == 0):
			print("hello")
		elif (x == 1 or x == 2):
			print("second or third")
		elif (x == 3):
			print("4")
		else:
			print("last x value left to check")

would print `"hello"`, `"second or third"`, `"second or third"`, `"4"`, `"last x value left to check"` with each string on a new line.

Notice how all the terms aren't just printed 5 times each as in the second example in the For-Loops section.