# Chapter 4: Control Structures and Logic

In this chapter, we will explore control structures and logic in programming. We will cover conditional statements like `if` and `else`, loops such as `for` and `while`, functions and modularity, and provide practical examples and exercises.

## Conditional Statements (If, Else)

Conditional statements are used to perform different actions based on different conditions. In Python, `if` and `else` are used for this purpose.

Here's a simple example:

```python
age = 18

if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```

In this example, if the age is 18 or more, the program will print "You are an adult." Otherwise, it will print "You are a minor."

## Loops (For, While)

Loops are used to repeat a block of code multiple times. Python has two types of loops - `for` and `while`.

Here's an example of a `for` loop:

```python
for i in range(5):
    print(i)
```

And here's an example of a `while` loop:

```python
i = 0
while i < 5:
    print(i)
    i += 1
```

Both of these loops will print the numbers 0 through 4.

## Functions and Modularity

Functions are blocks of code that perform a specific task. Functions help us achieve modularity in our code, making it more organized and manageable.

Here's an example of a function in Python:

```python
def greet(name):
    print("Hello, " + name + "!")

greet("Alice")
```

In this example, `greet` is a function that takes a name as an argument and prints a greeting. We then call the function with the argument "Alice".

## Practical Examples and Exercises

Now that we've covered the basics of control structures and logic, it's time for some practice. Try to solve the following exercises:

1. Write a program that prints the numbers from 1 to 10 using a `for` loop.
2. Write a program that prints the numbers from 1 to 10 using a `while` loop.
3. Write a function that takes a number as an argument and prints whether the number is even or odd.

In the next chapter, we will delve deeper into data structures and algorithms, which are essential for solving complex problems in programming.
