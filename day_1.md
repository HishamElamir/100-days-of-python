# Day 1 - Introduction to Programming and Python


## History of Programming

The history of programming languages spans back to the 19th century. In 1843, Ada Lovelace wrote the first computer algorithm for Charles Babbage's Analytical Engine, laying the foundation for modern programming12. The first recognizably modern electrically powered computers emerged in the 1940s, with programmers writing hand-tuned assembly language programs7.
In the 1950s, higher-level programming languages began to appear:

* **1957:** FORTRAN, created by John Backus for scientific and mathematical computations130
* **1958:** ALGOL, an algorithmic language that influenced many subsequent languages130
* **1959:** COBOL, developed by Grace Hopper for business applications130

The 1960s and 1970s saw the development of influential languages like BASIC (1964) and C (1972)1. Object-oriented programming gained prominence in the 1980s with languages like C++ (1983)1.


## History of Python
Python was conceived in the late 1980s by Guido van Rossum at the Centrum Wiskunde & Informatica (CWI) in the Netherlands336. Van Rossum began implementation in December 1989, aiming to create a successor to the ABC language that was capable of exception handling and interfacing with the Amoeba operating system336.
Key milestones in Python's history include:
* **February 1991:** First public release (version 0.9.0)
* **January 1994:** Python 1.0 released, introducing functional programming tools
* **October 2000:** Python 2.0 released, adding features like list comprehensions and garbage collection
* **December 2008:** Python 3.0 released, a major revision that was not backward-compatible with Python

Python's name was inspired by the British comedy series "Monty Python's Flying Circus," reflecting van Rossum's aim to make programming enjoyable.


### Python 2 vs Python 3
Python 3, released in 2008, introduced significant changes that were not backward-compatible with Python 2. Key differences include:

* Print function: In Python 3, print is a function, requiring parentheses.
* Division: Python 3 performs true division by default, returning a float.
* Unicode support: Python 3 uses Unicode for all strings by default.
* Range function: In Python 3, range() returns an iterator object instead of a list.
* Exception handling: Python 3 uses the as keyword for exception handling.

Python 2 reached its end-of-life on January 1, 2020, and is no longer supported. It's recommended to use Python 3 for all new projects due to its improved features, syntax, and ongoing support.

## Where to Write Code

### Code Editor

### Google Colab


## Writing Code

### Running Snippet of Python

```python
print("Hello Python interpreter!") 
```

### What Really Happened

Let’s take a closer look at what Python does when you run the line of code.
As it turns out, Python does a fair amount of work, even when it runs a simple program:

```python
print("Hello Python world!")
```

* What is `print` and what it does?
* Why there's `(` and `)`?
* Why there's `"`?

### Errors You Might Find
The following lines of code, seems to be the same as the one above, but you will find out that they don't work like the one we used.

This will produce error, as you have capitalized a character of the function `print` and used `Print` instead.
```python
Print("Hello Python world!")
```

Here, you capitalized all the function characters, which is totally wrong.
```python
PRINT("Hello Python world!")
```

Here, you used `{}` instead of `()`.
```python
print{"Hello Python world!"}
```

Here, you used one of `"` and the other one is `'`, if you started with `"` you should end with the same.
```python
print("Hello Python world!')
```

Here, you didn't use `"` or `'` around the string or text you need to print.
```python
print(Hello Python world!)
```
