## Loops

### Writing Loops

Loops are exactly what they sound like they are: pieces of code that runs in a pattern multiple times. Loops are useful for math (brute-force problems), reading data from a file (line-by-line), and many more.

There are two types of loops in Python: a `for` loop and a `while` loop.

#### For Loop

For loops begin with the keyword `for`. Its basic syntax looks like this:

```python
for element in iterable:
```

Here's an example of some code that prints `Hello, EasyCTF!` 5 times:

```python
for i in range(5):
    print "Hello, EasyCTF!"
```

In this example, `i` is the element, and `range(5)` is an iterable that literally contains the numbers `0, 1, 2, 3, 4`. More about the `range()` function can be found on [the Python documentation](https://docs.python.org/2/library/functions.html#range).



