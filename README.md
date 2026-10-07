# Cookie Jar 🍪

A Python class that simulates a cookie jar and keeps track of its capacity and the number of cookies inside it.

## About the Project

The project focuses on creating a `Jar` class that can store cookies up to a defined capacity.

The class allows cookies to be added and removed while making sure the jar never exceeds its capacity or contains a negative number of cookies.

The project also includes tests for checking the behavior of the class and its methods.

## Features

* Set a maximum cookie capacity
* Add cookies to the jar
* Remove cookies from the jar
* Check the current number of cookies
* Display the cookies as 🍪 emojis
* Validate capacity and cookie amounts
* Raise `ValueError` for invalid operations
* Test the class using `pytest`

## How It Works

A `Jar` object is created with a maximum capacity.

For example:

```python
jar = Jar(12)
```

Cookies can then be added:

```python
jar.deposit(3)
```

The current contents of the jar can be displayed:

```text
🍪🍪🍪
```

If adding more cookies would exceed the jar's capacity, the program raises a `ValueError`.

Cookies can also be removed using:

```python
jar.withdraw(1)
```

The class provides properties for checking both the maximum capacity and the current number of cookies.

## What I Practiced

While working on this project, I practiced:

* Creating classes
* Creating objects and instances
* Using `__init__`
* Using `__str__`
* Working with instance methods
* Using properties with `@property`
* Managing object state
* Raising `ValueError`
* Writing tests with `pytest`
* Using `assert` statements
* Testing different class behaviors

## Technologies

* Python
* Object-Oriented Programming
* pytest

## Testing

The project includes a separate test file called `test_jar.py`.

Run the tests with:

```bash
pytest test_jar.py
```

The tests cover initialization, string representation, depositing cookies, and withdrawing cookies.

## Course

This project was completed as part of **CS50's Introduction to Programming with Python** by Harvard University.
