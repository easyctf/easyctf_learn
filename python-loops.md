# Loops

## Writing Loops

Loops are exactly what they sound like they are: pieces of code that runs in a pattern multiple times. Loops are useful for math (brute-force problems), reading data from a file (line-by-line), and many more.

There are two types of loops in Python: a `for` loop and a `while` loop.

### For Loop

For loops begin with the keyword `for`. Its basic syntax looks like this:

```python
for element in iterable:
```

Here's an example of some code that prints `Hello, EasyCTF!` 5 times:

```python
for i in range(5):
    print "Hello, EasyCTF!"
```

And the output for this is exactly what you would think it is:

```
Hello, EasyCTF!
Hello, EasyCTF!
Hello, EasyCTF!
Hello, EasyCTF!
Hello, EasyCTF!
```

In this example, `i` is the element, and `range(5)` is an iterable that literally contains the numbers `0, 1, 2, 3, 4`. More about the `range()` function can be found on [the Python documentation](https://docs.python.org/2/library/functions.html#range).

In another example of a for loop, we will compute and print the sum of all of the integers less than 50,000.

```python
sum = 0
for i in range(50000):
    sum += i
print "The sum is %d" % sum
```

And our output is:

```
The sum is 1249975000
```

In this example, we can see that the value of the variable `i` changes every iteration. Its value is determined by the position in the iterable object, the `range(50000)`. For example, in the first iteration, `i` would be 0, and in the second iteration, `i` would be 1.





