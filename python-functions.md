## Functions
A function is a part of a program that can complete a certain task. For example, a function may be written that finds the average of three supplied numbers. Once written, it can be used many times without having to rewrite it over and over again.

### Writing Functions

To define: 

```python
def func_name():
```
	
Any code inside the function should be indented until you want to exit the function.

You can put parameters - information passed to the function for use inside it - in a function as well. Here is a simple example: 

```python
def func_name(a,b,c):
	print(a+b)
	print(c)
```	

`func_name(3,7,"Hello")` would print an output of:

```
10
"Hello"
```