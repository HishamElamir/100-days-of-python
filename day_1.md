# Day 1 - Introduction to Programming and Python


## History of Programming

## History of Python

### Python 2 vs Python 3


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