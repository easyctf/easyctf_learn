# Variables

Variables store values that can be looked at or changed later. You do not need to need to declare variable types before assigning them. However, you must initialize them before you call them. Different types of variables include:

## Integer

An integer is a number that is not a fraction.

Examples: `-1`, `2`, `105676`, etc.

To define an integer, use the following syntax: 

```python
myint = 2
```
	
## Floating Point

A number that has decimal values. 

Examples: `1.0`, `-2.73`, `0.66`

To define:

```python
myfloat = 7.3
```
	
or

```python
myfloat = float(7)
```
	
With integers and floating points, you can perform basic math operations on them such as `+ - / *` (with integers though, your answers will be rounded down to an integer).

## String

Text surrounded by double or single quotes.  

Examples: `"Hello"`, `'World'`

To define: 

```python
hello = "Hello"
world = "World"
```
	
You can also add strings together like this: 

```python
helloworld = hello + " " + world
```
	
This makes `helloworld` store the value `"Hello World"`

Or multiply a string with an integer to get a repeating string such as:

```python
helloworld = "hello" * 6 + 3 * "world"
```

Which makes `helloworld` store the value `"hellohellohellohellohellohelloworldworldworld"`

#### PLEASE DO NOT SUBTRACT OR DIVIDE STRINGS

## Character


A single symbol represented by a letter or number surrounded by single quotes. 

Examples: `'A'`, `'4'`, `'k'`

To define: 

```python
mychar = 'h'
```
	
Single characters can be converted to their ASCII identifiers using the `ord()` function. Similarly, to convert an ASCII identifier back to a readable character, use the `chr()` function.

Python also has a useful type called a list. It's exactly what it sounds like, it's a way to store items in a non orderd way. Here's a quick example:

```python
students = ["James", "Jim", "Bob", "Freyja the Norse mythological diety", "Sally"]
```
Elements of a list can be accesed via indicies, i.e. students[0] returns the first element.
You can add to a list by .appending() something.
Say I wanted to get a nice representation of all the students in my class:
```python
Students enrolled in the School for Procrastination:
print ', '.join(students)
```
Another useful python type is the tuple, this is somewhat similar to the list, but the difference is that this is ordered. Not ordered in the sense that one is larger than the order, but think of a coordinate system, (x,y).
That's how a tuple works. 
```python
battle_ship_location = ("B", 7) 
print "HIT"
```
