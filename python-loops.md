## Loops

### Writing Loops

Loops are exactly what they sound like they are: pieces of code that runs in a pattern multiple times. Loops are useful for math (brute-force problems), reading data from a file (line-by-line), and many more.

There are two types of loops in Python: a `for` loop and a `while` loop.

#### For Loop

For loops begin with the keyword `for`. Its basic syntax looks like this:

    for element in iterable:

Here's an example of some code that prints `Hello, EasyCTF!` 5 times:

```python
for i in range(5):
    print "Hello, EasyCTF!"
```

