## Loops

### Writing Loops

For-Loops will come in handy during the competition, especially in challenges that ask you to brute force answers. Basically, a for loop will repeat whatever code is inside it a certain number of times. 

To define: 

	for x in range(a,b,c):
	
What this means is for each number `x` inside the range `[a,b)`, meaning the range includes `a` but doesn't include `b`, it will skip every `c` number (if you don't include a `c` parameter, it will default to just incrementing by 1)

For example:

	for x in range(0,10,2):
		print(x)

would print `0,2,4,6,8`, with each number on a new line.

Another example:

	for x in range(0,5):
		print("hello")

would print `"hello"` 5 times, which each "hello" on a new line.